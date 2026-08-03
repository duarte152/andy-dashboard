# Memory Index

*Last updated: 2026-06-15*
*Consultar este índice para encontrar o arquivo certo antes de iniciar qualquer tarefa.*

---

## Leitura Obrigatória no Início de Sessão

| Arquivo | Conteúdo |
|---------|----------|
| `NOW.md` | Estado atual consolidado — prioridades ativas, próximos passos, datas críticas (fonte de verdade vigente) |
| `preferences.md` | Regras comportamentais, regras de email, acesso ao Gmail, protocolo de memória, arquitetura de memória |
| `thiago_profile.md` | Perfil completo: identidade, carreira, projetos, metas, rotina, nutrição |

---

## Arquitetura de Memória (adotado 25/07/2026)

| Arquivo | Conteúdo |
|---------|----------|
| `log.md` | Registro cronológico append-only — 1 linha por decisão/sessão relevante |
| `inbox.md` | Entrada bruta não classificada (exceção, não fluxo principal — triar rápido) |
| `ideias.md` | Backlog de ideias soltas que ainda não viraram projeto ativo |

---

## Notion (segundo cérebro de candidaturas)

**Status: estrutura completa construída em 25/07/2026** — 7 páginas (raiz + 6 subpáginas), condensando os arquivos locais abaixo. Notion = visão condensada/navegável e compartilhada com Thiago; os arquivos `.md` locais continuam sendo a versão completa/fonte de detalhe.

| Arquivo / Página | Conteúdo |
|---------|----------|
| `.notion_key` | Token da integração interna do Notion (API) |
| `notion_helpers.py` | Toolkit Python (urllib) para criar/editar blocos via API do Notion — reusar em vez de recriar |
| `attachments/design-system-notion.txt` | **Guia obrigatório de sintaxe + convenções estéticas** para qualquer página escrita no Notion (Notion-flavored Markdown) — ler antes de criar/editar página |
| [🧠 Segundo Cérebro (Thiago)](https://app.notion.com/p/Segundo-C-rebro-Thiago-3a81f7dcf5b580fd86abd8ea0dea631c) | **Página raiz** — dashboard com status das 3 frentes, hierarquia de confiança, regra de autonomia, link para as 6 subpáginas abaixo |
| [🎨 Design System - Regras de Formatação](https://app.notion.com/p/Design-System-Regras-de-Formata-o-3a81f7dcf5b581a1b43be6277c3d3f51) | Espelho no próprio Notion do `design-system-notion.txt` — regras de formatação a seguir sempre |
| [🎓 Chevening](https://app.notion.com/p/Chevening-3a81f7dcf5b581718beee434604d9239) | Versão condensada de `chevening_pesquisa.md` + essays — status, datas, pendências |
| [🎓 UK CDT/DTP](https://app.notion.com/p/UK-CDT-DTP-3a81f7dcf5b58142bd5ef28d8fb5a108) | Versão condensada de `plano_candidatura_uk_cdt.md` — programas, calendário, virtual coffees |
| [🎓 MPhil USyd (Carrigan)](https://app.notion.com/p/MPhil-USyd-Carrigan-3a81f7dcf5b58110958ef16d4ee61973) | Versão condensada de `plano_mphil_usyd.md` — status, deadline RTP, próximos passos |
| [🗒️ Log](https://app.notion.com/p/Log-3a81f7dcf5b58148a0b4c33a5fd62b84) | Espelho no Notion do `log.md` — registro cronológico |
| [💡 Ideias / Backlog](https://app.notion.com/p/Ideias-Backlog-3a81f7dcf5b5815fb128d1b399a240bb) | Espelho no Notion do `ideias.md` — ainda vazio, pronto para uso |
| [🏆 Aprovados em Chevening — Pesquisa de Práticas](https://app.notion.com/p/Aprovados-em-Chevening-Pesquisa-de-Pr-ticas-3a81f7dcf5b58194a09df9fd7dc7573c) | Subpágina de 🎓 Chevening. Compilado de práticas de ~30 aprovados reais (LatAm, África, Ásia, Oriente Médio), por ensaio + casos de rejeição→aprovação. Detalhe completo em `chevening_aprovados_pesquisa.md` |
| `chevening_aprovados_pesquisa.md` | Pesquisa completa (todas as fontes com detalhe integral) que originou a página acima — usar como matéria-prima para o Thiago escrever os próprios ensaios |
| `build_notion_aprovados.py` | Script usado para gerar a página acima — referência de como popular páginas grandes com toggles/tabelas via `notion_helpers.py` |

---

## Mestrado no Exterior

| Arquivo | Conteúdo |
|---------|----------|
| `mestrado_pesquisa.md` | Pesquisa geral sobre mestrado no exterior |
| `supervisores_australia.md` | Lista de supervisores identificados na Austrália (USyd, UNSW etc.) |
| `supervisores_uk.md` | Lista de supervisores identificados no Reino Unido |
| `supervisores_mcgill.md` | Supervisores identificados na McGill (Canadá) para McCall MacBain |
| `supervisores_stanford_mse.md` | Supervisores para Stanford MSE |
| `research_proposal_australia.md` | Rascunho da proposta de pesquisa para Austrália |
| `statement_of_purpose.md` | Statement of Purpose base |
| `sop_uk_personalizados.md` | SOPs personalizados para universidades do Reino Unido |
| `sop_stanford_mse.md` | SOP para Stanford MSE |

## Emails para Supervisores

| Arquivo | Conteúdo |
|---------|----------|
| `ajustes_emails_supervisores.md` | **REGRAS GLOBAIS de estilo e conteúdo para todos os emails** |
| `supervisor_email_template.md` | Template base + checklist pré-envio |
| `emails_supervisores_prontos.md` | Emails prontos (Austrália + outros) |
| `emails_supervisores_uk.md` | Emails para supervisores UK - batch 1 |
| `emails_supervisores_uk_batch2.md` | Emails para supervisores UK - batch 2 |
| `emails_supervisores_eua.md` | Emails para supervisores EUA - batch 1 |
| `emails_supervisores_eua_batch2.md` | Emails para supervisores EUA - batch 2 |
| `emails_supervisores_canada.md` | Emails para supervisores Canadá — histórico (batch original suspenso 10/05, novo mapeamento McGill 21/07) |
| `emails_supervisores_mcgill.md` | Emails prontos para Buckeridge e Pant Pai (McGill) — verificação Regra 13 concluída, 22/07/2026 |
| `emails_followup.md` | Templates de follow-up (14 dias sem resposta) |
| `baysari_email_v2.md` | Email específico para Prof. Baysari (USyd) |
| `ajustes_emails_supervisores.md` | Regras e ajustes consolidados (abril/2026) |

## Bolsas e Programas

| Arquivo | Conteúdo |
|---------|----------|
| `bolsas_internacionais_pesquisa.md` | Pesquisa geral sobre bolsas internacionais |
| `rtp_pesquisa.md` | Research Training Program (Austrália) |
| `chevening_pesquisa.md` | Bolsa Chevening (Reino Unido) |
| `chevening_essay_lideranca.md` | Essay de liderança para Chevening |
| `chevening_essays_restantes.md` | Demais essays Chevening |
| `knighthennessy_pesquisa.md` | Knight-Hennessy (Stanford) |
| `knighthennessy_essay_lideranca.md` | Essay de liderança Knight-Hennessy |
| `mccallmacbain_pesquisa.md` | McCall MacBain (McGill) |
| `mccallmacbain_narrativa.md` | Narrativa para McCall MacBain |
| `mccallmacbain_recomendadores.md` | Recomendadores para McCall MacBain |
| `fulbright_research.md` | Bolsa Fulbright (EUA) |
| `erasmus_pesquisa.md` | Programa Erasmus |
| `canada_pesquisa.md` | Pesquisa sobre mestrado no Canadá |
| `swedish_pesquisa.md` | Pesquisa sobre programas na Suécia |
| `rtp_pesquisa.md` | RTP Austrália |

## CV e Perfil Profissional

| Arquivo | Conteúdo |
|---------|----------|
| `cv_english.md` | CV em inglês (texto) |
| `cv_thiago_rocha_duarte.html` | CV em HTML |
| `cv_thiago_rocha_duarte.pdf` | CV em PDF |
| `linkedin_strategy.md` | Estratégia para LinkedIn |
| `metricas_impacto_khs.md` | Métricas de impacto (Knight-Hennessy) |

## MPhil USyd — Plano de Ação

| Arquivo | Conteúdo |
|---------|----------|
| `plano_mphil_usyd.md` | Plano completo com cronograma para entregar proposta à Carrigan (USyd) — deadline RTP: 18/Dez/2026 |
| `carrigan_scoping_review_notes.md` | Notas do review não publicado da Carrigan (SEIPS + DHIs) — metodologia, bases de dados, estrutura |
| `mphil_usyd_pesquisa_literatura.md` | Busca piloto de literatura (Fase 1A) no PubMed (25/07) + expansão (26/07) com novos termos (endoscopist, dermatology AI, CDSS+SEIPS) + **rastreamento das fontes das 2 revisões-guarda-chuva (03/08 noturna)**: 4 estudos novos identificados dentro de Lawrence 2025/Wenderott 2025, sem sobreposição — matriz agora com 10 estudos. Confirmado: nenhum estudo primário combina radiologistas+patologistas nem usa SEIPS 2.0 como lente qualitativa primária — gap segue validado em 3 níveis independentes |
| `attachments/SEIPS review_final_App Erg.docx` | Arquivo original do scoping review da Carrigan (não publicado — não compartilhar) |

## Candidatura UK — CDTs e Chevening

| Arquivo | Conteúdo |
|---------|----------|
| `plano_candidatura_uk_cdt.md` | **PLANO PRINCIPAL UK** — programas CDT/DTP mapeados, prereqs, estratégia de entrevistas com alunos, personal statement, calendário de aplicações |
| `waty_call_notes.md` | Notas brutas da call com Dr. Waty Lilaonitkul (27/05/2026) — estratégia de candidatura, dicas de personal statement, orientação sobre CDTs |
| `supervisores_uk.md` | Supervisores identificados (UCL, Imperial, Edinburgh) — Dr. Waty é contato ativo |
| `chevening_pesquisa.md` | Pesquisa completa sobre a Chevening scholarship — portal abre agosto 2026 |
| `chevening_essay_lideranca.md` | Essay de liderança Chevening (redigido) |
| `chevening_essays_restantes.md` | Demais 3 essays Chevening (redigidos) |
| `chevening_essay_framework.md` | Framework de essay consolidando conselhos da Waty (Personal Impact/Vision/Give Back) + Will, alumnus Chevening/UCL (Why UK / Why this course "jigsaw puzzle" / Why now) — usar como base ao redigir "why this course" |

## Outros

| Arquivo | Conteúdo |
|---------|----------|
| `relatos_brasileiros.md` | Relatos de brasileiros no exterior |
| `plano_noturno.md` | Plano noturno / rotina |
| `dashboard.html` | Dashboard de acompanhamento das aplicações |

## Histórico de Conversas

Pasta `conversations/` - 22 arquivos de sessões anteriores (abr-mai/2026).
Para buscar contexto: `grep -rl "palavra-chave" /workspace/group/conversations/`
