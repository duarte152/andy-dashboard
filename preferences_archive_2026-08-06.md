# Preferences & Standing Rules

*Last updated: 2026-06-15*
*Este arquivo deve ser lido no início de toda sessão.*

---

## Regras Comportamentais

### Emails
- **SEMPRE salvar como rascunho no Gmail, nunca enviar diretamente** — Thiago revisa e envia manualmente. Regra confirmada em 22/07/2026 ("rascunho sempre").

### Espanhol
- Quando Thiago estiver praticando espanhol, falar SOMENTE em espanhol - zero português
- Corrigir SEMPRE que houver erro ou algo que soe não natural, ensinando a forma correta
- Não deixar passar nenhum erro sem corrigir

### Calorias e Proteínas
- Somar calorias e proteínas ingeridas ao longo do dia
- Informar o total acumulado SEMPRE que Thiago atualizar a ingestão
- Whey: 127 cal, 23g proteína por porção

---

## Regras de Comunicação

- Tom casual/coloquial na conversa do dia a dia
- Respostas práticas, claras, inteligentes e personalizadas - nunca genéricas
- Não fazer perguntas genéricas que travam a conversa
- Opiniões diretas são bem-vindas
- Oferecer sempre próximos passos acionáveis
- Formal apenas quando o contexto exige (ex: redigir email ou documento formal)

---

## Regras para Emails e Documentos Formais

Ver arquivo completo: `ajustes_emails_supervisores.md`

Resumo dos pontos críticos (aplicar a QUALQUER email redigido):

- **PROIBIDO em dash (—)** - sempre hífen simples (-)
- **Assinatura padrão obrigatória:**
  ```
  Thiago Rocha Duarte
  Product Specialists & Product Enablement Lead, Laudite

  https://www.linkedin.com/in/thiago-rocha-duarte-6982341b1/?locale=en_US
  ```
- Sem "I hope this message finds you well" ou openers genéricos
- Sem mencionar nacionalidade no primeiro parágrafo
- Laudite = plataforma GenAI para laudos médicos (NÃO CDSS)
- Consultar `ajustes_emails_supervisores.md` ANTES de redigir qualquer email acadêmico/profissional

---

## Groq API (Transcrição de Voz)

- API Key salva em: `/workspace/group/.groq_key`
- Modelo: `whisper-large-v3-turbo` (grátis, multilíngue: PT, EN, ES, etc.)
- Script: `python3 /workspace/group/transcribe.py <arquivo.oga>`
- Funciona via curl (Python urllib bloqueado pelo Cloudflare)

---

## Bloqueios de fetch automatizado por domínio (padrão recorrente)

Alguns domínios bloqueiam clientes HTTP automatizados (WebFetch, curl, urllib, web.archive.org) mas **liberam navegador real**. Confirmado em `chevening.org/news/*` (25/07/2026): WebFetch/curl/wayback deram timeout consistente durante toda uma pesquisa; `agent-browser open` + `agent-browser snapshot -c` funcionou de primeira, sem nenhum bloqueio. Provável proteção anti-bot (Cloudflare-like) que decide pelo user-agent/execução de JS.
**Regra prática:** se um domínio bloquear WebFetch/curl, tentar `agent-browser` (skill de automação de navegador) antes de desistir ou reportar "inacessível" ao Thiago.

---

## Notion API

- Token da integração interna salvo em: `/workspace/group/.notion_key`
- Uso: `curl -H "Authorization: Bearer $(cat /workspace/group/.notion_key)" -H "Notion-Version: 2022-06-28" ...`
- Acesso via REST API direta (sem MCP) — mesmo padrão do Gmail/GitHub/Groq
- A integração só enxerga páginas/databases explicitamente conectadas pelo Thiago (menu "•••" → Connections na página do Notion)
- Endpoint de busca: `POST https://api.notion.com/v1/search` lista o que está conectado
- Status: **estrutura completa construída em 25/07/2026.** Página raiz conectada: [🧠 Segundo Cérebro (Thiago)](https://app.notion.com/p/Segundo-C-rebro-Thiago-3a81f7dcf5b580fd86abd8ea0dea631c) (id `3a81f7dc-f5b5-80fd-86ab-d8ea0dea631c`), com 6 subpáginas (Design System, Chevening, UK CDT/DTP, MPhil USyd, Log, Ideias/Backlog) — ver lista completa e URLs em `memory_index.md`. Toolkit reusável de blocos em `notion_helpers.py`.
- **Design system obrigatório ao escrever qualquer página no Notion:** `attachments/design-system-notion.txt` — guia de sintaxe (Notion-flavored Markdown: callout, toggle, mermaid, colunas, tabelas) + convenções estéticas (variar blocos, emoji consistente, cores semânticas, impessoalidade, checklist pré-publicação). Ler ANTES de criar/editar qualquer página no Notion, sem exceção.

---

## Gmail

- Acesso via IMAP: `imaplib.IMAP4_SSL("imap.gmail.com", 993)`
- Usuário: `thiago.duarte152@gmail.com`
- App Password: `cxjv nooh nwmw hctf`
- Pasta de rascunhos: `[Gmail]/Rascunhos`
- Pasta com todos os emails (inbox + enviados + tudo): `[Gmail]/Todos os e-mails` — usar essa para buscar por remetente/assunto, não a INBOX sozinha
- **IMPORTANTE:** Antes de dizer "não tenho acesso ao Gmail" ou tentar `ToolSearch` por ferramentas externas, SEMPRE usar IMAP diretamente via Bash/Python com as credenciais acima. Não é preciso pedir ao Thiago o conteúdo de emails — eu já tenho acesso.
- Exemplo de busca: `M.select('"[Gmail]/Todos os e-mails"'); M.search(None, '(FROM "nome")')` depois `M.fetch(id, '(RFC822)')` e parsear com `email.message_from_bytes`.

---

## Protocolo de Escrita de Memória

Quando Thiago disser "sempre", "nunca", "de agora em diante", "lembra que", "guarda isso" ou qualquer instrução recorrente:
1. Escrever imediatamente neste arquivo (`preferences.md`)
2. Confirmar no chat: "Salvo em preferences.md"

---

## Arquitetura de Memória (adotado 25/07/2026)

Após revisão de um framework de "segundo cérebro" trazido pelo Thiago, formalizei as seguintes regras. Ver `log.md` para o racional completo dessa decisão.

### Hierarquia de confiança
**Fonte de verdade vigente vence recência solta.** `NOW.md` é a fonte de verdade consolidada das prioridades ativas — uma menção solta numa conversa antiga ou num arquivo de pesquisa desatualizado NUNCA sobrepõe o que está em `NOW.md`, até que `NOW.md` seja explicitamente atualizado. Em caso de conflito entre um arquivo de pesquisa (ex: `chevening_pesquisa.md`) e `NOW.md`, `NOW.md` vence.

### Arquivos de apoio à memória
- `log.md` — registro cronológico append-only, 1 linha por decisão/sessão relevante. Só adicionar no topo, nunca editar entradas antigas. Não confundir com `NOW.md` (que é o estado atual consolidado, sobrescrito a cada atualização).
- `inbox.md` — exceção, não fluxo principal. Só usar quando algo chegar e não estiver claro em qual arquivo/projeto encaixar. Triagem deve acontecer o quanto antes; não deixar acumular.
- `ideias.md` — backlog de ideias soltas que ainda não são projeto ativo. Quando uma ideia ganha tração, ela sai de lá, vira arquivo/prioridade própria, e isso é registrado em `log.md`.

### Regra de autonomia (o que escrevo livre vs. o que só faço se pedido)
- **Escrevo livremente sem pedir:** `log.md`, `inbox.md`, arquivos de pesquisa (research), `thiago_profile.md` e `preferences.md` quando surge fato novo ou regra nova (protocolo já existente), `memory_index.md`.
- **Só escrevo/edito quando Thiago pede ou confirma explicitamente:** qualquer email (sempre rascunho, nunca enviar), essays e textos de candidatura (Chevening, SOPs, cartas), decisões estratégicas sobre escolha de programa/universidade, e qualquer coisa que represente uma decisão ou posicionamento do próprio Thiago (não meu). Isso evita eu "inventar" posicionamento que ele nunca validou.
- **Meio-termo (pergunto antes):** reestruturação de arquivos existentes, renomear/apagar coisa que já existe, mudanças que afetam vários arquivos de uma vez.

### Fontes imutáveis
Arquivos em `attachments/` (documentos enviados pelo Thiago, PDFs, anexos originais) são fonte imutável — leio e refiro, mas nunca edito o conteúdo original.

### Nota sobre migração para Notion
A ideia de quebrar `NOW.md` num arquivo por projeto com frontmatter (status/created/updated) foi discutida mas **adiada de propósito** — faz mais sentido desenhar isso já pensando em Notion (databases nativas) quando o MCP for configurado, em vez de reestruturar aqui em markdown e reestruturar de novo depois. Até lá, `NOW.md` continua único e consolidado.
