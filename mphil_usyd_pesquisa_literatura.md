# MPhil USyd (Carrigan) — Pesquisa Piloto de Literatura (Fase 1A)
*Criado por Andy em 25/07/2026 (sessão noturna) — avanço real da Fase 1 do `plano_mphil_usyd.md`*

---

## Objetivo desta pesquisa

O `plano_mphil_usyd.md` (Fase 1A) previa buscas sistemáticas em 4 bases (Medline/PubMed, PsycINFO, Web of Science, CINAHL) para o scoping review proposto à Dr. Carrigan sobre **experiências qualitativas de diagnosticistas (radiologistas/patologistas) usando ferramentas de IA de suporte diagnóstico, sob lente de human factors/sociotechnical systems (SEIPS 2.0)**.

Essa fase estava pendente desde 17/06/2026 (Fase 0 concluída, Fase 1 nunca iniciada). Em vez de repetir pela enésima vez a verificação dos itens 1 e 2 da tarefa noturna recorrente (`supervisores_uk.md` e `chevening_essay_lideranca.md` — ambos verificados, íntegros, sem alterações necessárias, ver `plano_noturno.md`), usei o tempo real da sessão para uma **busca piloto no PubMed** (Fase 1A em escala reduzida) — o item pendente de maior prioridade real segundo o `NOW.md`.

---

## ⚠️ ACHADO CRÍTICO — Revisão já existente que se sobrepõe parcialmente ao tema

**Lawrence R, et al. "Artificial intelligence for diagnostics in radiology practice: a rapid systematic scoping review." eClinicalMedicine. 2025 May 12;83:103228.** (PROSPERO CRD42024537518, PMCID PMC12140059)

- **Escopo:** scoping review formal, 8.013 artigos triados, **140 estudos incluídos**, cobrindo: implementação (N=7), percepções (N=74), experiências (N=14), efetividade quantitativa (N=53) e custo (N=6).
- **Por que importa:** é uma revisão grande, recente (maio/2025) e financiada pelo NIHR (UK), com metodologia rigorosa (PRISMA, workshops com stakeholders). Cobre parcialmente o mesmo território que Thiago propôs à Carrigan.
- **Por que NÃO invalida a proposta de Thiago** (diferenciação clara a usar no Background/Problem):
  1. **Radiologia apenas** — não inclui patologistas nem outros diagnosticistas por imagem. A proposta de Thiago cobre radiologistas *e* patologistas.
  2. **Sem lente teórica de human factors dedicada** — a revisão de Lawrence et al. mistura implementação, percepções (majoritariamente surveys quantitativos), experiências e custo, sem aplicar um framework sociotécnico único (como SEIPS 2.0) para sintetizar os achados qualitativos.
  3. **"Experiência" é uma fatia pequena e não aprofundada** — apenas 14 dos 140 estudos (10%) tratam de experiência propriamente dita; os outros 74 de "percepções" são majoritariamente pesquisas de atitude/survey, não dados qualitativos ricos.
  4. **Os próprios autores confirmam o gap**: na seção "Implications of all the available evidence", eles pedem explicitamente mais pesquisa sobre "*experiences of using AI in practice*" — exatamente o núcleo da proposta de Thiago.
- **Uso recomendado na proposta:** citar Lawrence et al. 2025 no Background como a revisão mais abrangente e recente sobre o tema geral, e usar exatamente os limites dela (radiologia-only, síntese rasa de experiência, ausência de framework sociotécnico) para articular o gap específico e mais estreito da proposta de Thiago. Isso fortalece a proposta ao mostrar que ele conhece a literatura mais recente — não a ignora.
- **Nota metodológica:** eles registraram o protocolo no **PROSPERO**, não OSF. Vale considerar PROSPERO como alternativa ao OSF mencionado no plano original (Fase 2F) — pode ser mais reconhecido para reviews em saúde.

---

## Matriz de literatura (piloto — 6 estudos mapeados)

| # | Estudo | Ano | Amostra/Método | Foco | Framework teórico | Relevância p/ gap de Thiago |
|---|--------|-----|-----------------|------|---------------------|------------------------------|
| 1 | Lawrence et al. — rapid scoping review (eClinicalMedicine) | 2025 | 140 estudos incluídos | Implementação, percepções, experiência, efetividade, custo | Nenhum framework sociotécnico único | **Revisão-guarda-chuva** — usar para diferenciação do gap (radiologia-only, síntese rasa de "experiência") |
| 2 | **[JMIR Human Factors] "The Promise of AI for Image-Driven Medicine"** — qualitative interview study | 2024 | 21 participantes (7 patologistas, 10 radiologistas, 4 cientistas de computação); COREQ; thematic analysis (Braun & Clarke) | Percepções/expectativas sobre papel profissional e IA | Nenhum framework SEIPS/sociotécnico explícito — lente de identidade profissional | **Estudo mais próximo do tema de Thiago** (único que combina radiologistas + patologistas numa mesma amostra qualitativa). Diferencial de Thiago: aplicar SEIPS 2.0 explicitamente, o que este estudo não faz |
| 3 | NASSS framework implementation study (JMIR) — "Implementing an AI Decision Support System in Radiology" | 2026 (early view) | 43 entrevistas semiestruturadas, 3 fases (pré/peri/pós-implementação), hospital público em Brisbane (Austrália) | Implementação, fatores organizacionais/humanos | **NASSS** (framework sociotécnico, primo do SEIPS) | Radiologia apenas, Austrália — bom para contextualizar relevância local (USyd/Austrália) na proposta; mostra que NASSS já é usado no campo, reforça pertinência de framework sociotécnico (SEIPS) |
| 4 | Radiology Staff Experiences — Swedish qualitative case study (JMIR Formative Research) | 2025 | 12 participantes (7 radiologistas, 4 tecnólogos, 1 assistente médico), 1 hospital sueco | Experiência de integração de IA na prática | Não especificado (case study) | Radiologia apenas, amostra pequena, single-site — mostra literatura ainda fragmentada/local, reforça necessidade de síntese |
| 5 | Pathologists' perceptions towards AI-assisted diagnostic systems (PLOS Digital Health) | 2024 | Estudo quantitativo (survey) | Percepções de patologistas | Nenhum | **Quantitativo, não qualitativo** — confirma que a literatura sobre patologistas tende a ser survey-based, não qualitativa/experiencial (reforça o gap) |
| 6 | Radiology Residents' Perceptions — nationwide cross-sectional survey (China) | 2023 | 3.666 residentes, survey | Percepções sobre IA | Nenhum | Quantitativo, grande N — mesmo padrão do #5: percepção via survey, não experiência qualitativa aprofundada |

---

## Leitura preliminar do gap (achado principal)

A busca piloto **confirma e refina** a hipótese original do plano de Thiago:

1. **A literatura quantitativa sobre percepções/atitudes é abundante** (surveys grandes, centenas a milhares de respondentes — radiologia e patologia separadamente).
2. **A literatura qualitativa sobre experiência real de uso é escassa e fragmentada**: poucos estudos (single-site, amostras pequenas de 12-43 participantes), a maioria só em radiologia, cada um usando uma lente teórica diferente (nenhuma consistentemente SEIPS) ou nenhuma lente teórica.
3. **Nenhum estudo ou revisão encontrado até agora combina**: (a) radiologistas E patologistas juntos, (b) foco exclusivamente qualitativo/experiencial (não misturado com survey de percepção ou dados de efetividade), (c) framework SEIPS 2.0 explícito como lente de análise sociotécnica.
4. Esse é exatamente o espaço vazio que a proposta de Thiago pode ocupar — e agora com evidência concreta (não só hipótese) para citar no Background.

**Achado bônus:** o estudo #3 (NASSS, Brisbane) é australiano — pode ser citado na proposta como evidência de que o tema já tem tração de pesquisa na Austrália, reforçando o fit institucional com a USyd/Carrigan.

---

## O que NÃO foi feito (deixado para sessão dedicada com Zotero)

- Busca sistemática completa nas 4 bases (isso foi só PubMed/web, piloto de ~10 buscas)
- Registro formal no Zotero com os 6 estudos encontrados (fazer quando Thiago tiver Zotero instalado — ver Fase 0.2 do plano original)
- Screening formal título/abstract com critérios de inclusão/exclusão definidos
- Leitura de texto completo dos 6 estudos (só abstracts/resumos foram lidos)
- PsycINFO, Web of Science e CINAHL não pesquisados ainda (aguardam acesso institucional USyd, conforme já previsto no plano original)

---

## Próximos passos recomendados

1. Thiago instalar Zotero + configurar Vancouver style (Fase 0.2, ainda pendente)
2. Andy pode continuar a busca piloto em sessões futuras, expandindo para mais termos (ex: "endoscopist", "dermatology AI", "clinical decision support system" isolado de "diagnostic")
3. Ao escrever o Background da proposta (Fase 2A do plano original), usar Lawrence et al. 2025 como a citação-âncora para "o que já existe" e os achados #2-#6 acima como evidência da natureza fragmentada da literatura qualitativa existente
4. Considerar registrar o protocolo no **PROSPERO** em vez de (ou além de) OSF, já que é o registro usado pela revisão mais próxima do campo (Lawrence et al. 2025)

---

*Arquivo de pesquisa — escrito livremente por Andy (autonomia de pesquisa, ver `preferences.md`). Não decide posicionamento final do Thiago; é matéria-prima para a Fase 2 (escrita do summary), que segue exigindo confirmação/revisão dele antes de qualquer envio à Carrigan.*
