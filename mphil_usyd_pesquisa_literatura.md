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

---

## Expansão da busca piloto (26/07/2026, sessão noturna)

Continuação da Fase 1A conforme sugerido no "Próximos passos" acima (item 2): busca com termos adicionais — "endoscopist", "dermatology AI", "clinical decision support system" isolado de "diagnostic" + sociotechnical/SEIPS.

### ⭐ Novo achado importante — segunda revisão-guarda-chuva que reforça o gap

**Wenderott K, Krups J, Weigl M, Wooldridge AR. "Facilitators and Barriers to Implementing AI in Routine Medical Imaging: Systematic Review and Qualitative Analysis." J Med Internet Res. 2025 Jul 21;27:e63649.**

- Systematic review, 6 bases de dados, 13.756 registros triados, **38 estudos incluídos**. Identificou 12 dimensões e 37 subtemas que influenciam implementação de IA em imaging.
- **Frase-chave para citar diretamente na proposta:** os autores relatam que os estudos **"focused predominantly on performance metrics over the experiences or outcomes of clinicians"** — ou seja, a própria revisão mais recente e ampla sobre implementação de IA em imaging médico confirma, com dados sistemáticos, que a experiência do clinico é sub-representada face às métricas de performance. Isso é evidência direta e quotável do gap que a proposta de Thiago ataca.
- Também usa lente sociotécnica (protocolo relacionado: "Integration of Artificial Intelligence Into Sociotechnical Work Systems" — JMIR Research Protocols 2022) — reforça a pertinência de um framework como SEIPS 2.0.
- **Recomendação:** citar Wenderott et al. 2025 **junto com** Lawrence et al. 2025 no Background — duas revisões-guarda-chuva de 2025, ambas em imaging, ambas confirmando o mesmo gap por ângulos diferentes (Lawrence: pouca fatia "experiência" nos 140 estudos; Wenderott: foco em métricas de performance sobre experiência/outcomes do clínico nos 38 estudos de implementação).

### Outros achados da expansão

| Tema buscado | Resultado | Relevância |
|---|---|---|
| **Endoscopista + IA qualitativo** | Literatura sobre IA em endoscopia (colonoscopia, EGD) é quase toda **quantitativa** — detection rate, deskilling (ex: Lancet Gastro & Hepatology 2025 sobre risco de "deskilling" de endoscopistas após exposição a IA). Nenhum estudo qualitativo sobre experiência de endoscopistas com IA encontrado. | Confirma que endoscopistas (público que a Laudite também atende) são um grupo **ainda mais desprovido** de pesquisa qualitativa do que radiologistas/patologistas — reforça a relevância prática da proposta, mesmo que o escopo formal do MPhil continue radiologia+patologia (não expandir escopo sem alinhar com Carrigan) |
| **Dermatologia + IA qualitativo** | Existem estudos qualitativos de entrevista nessa área — ex: "Exploring the Views of Dermatologists, GPs, and Melanographers on the Use of AI Tools... Qualitative Interview Study" (JMIR Dermatology 2025, 30 clínicos, Austrália/NZ) e estudo similar com 29 stakeholders (2024) sobre detecção precoce de câncer de pele | São radiologia/patologia-adjacentes (diagnóstico por imagem de pele, não radiologia/patologia clássica) — **fora do escopo direto da proposta**, mas úteis como comparador metodológico: mostram que entrevista qualitativa semiestruturada é o desenho padrão da área, validando a escolha metodológica de Thiago. Nota: um desses é australiano (Austrália/NZ) — outro ponto de fit institucional com a USyd, como o achado NASSS de Brisbane já registrado |
| **CDSS isolado + sociotécnico/SEIPS** | Confirma padrão já visto: SEIPS aparece mais em estudos de segurança/workflow geral (ex: estudo 2026 sobre CDSS de transfusão de sangue, PMC12881895) do que especificamente em diagnóstico por imagem. Também localizado: "Barriers to and Facilitators of Artificial Intelligence Adoption in Health Care: Scoping Review" (JMIR Human Factors 2024) — outra revisão-guarda-chuva ampla (todo o setor de saúde, não só imaging) | Confirma que SEIPS 2.0 aplicado especificamente a diagnosticistas de imagem (radiologia+patologia) continua um espaço pouco ocupado — nenhuma das revisões encontradas até agora (Lawrence 2025, Wenderott 2025, JMIR Human Factors 2024) aplica SEIPS como lente central em diagnóstico por imagem |

### Leitura atualizada do gap (após expansão)

Com dois achados de revisões-guarda-chuva de 2025 (Lawrence + Wenderott) confirmando de formas independentes que a experiência do clínico é sub-representada face a métricas técnicas/de performance, a proposta de Thiago tem agora **duas citações-âncora** fortes e recentes para abrir o Background, além da matriz de estudos individuais já mapeada na sessão anterior.

---

---

## Rastreamento das fontes das revisões-guarda-chuva (03/08/2026, sessão noturna)

Continuação do "próximo passo sugerido" da sessão de 26/07: buscar diretamente pelos estudos individuais citados dentro de Lawrence et al. 2025 (14 estudos de "experiência") e Wenderott et al. 2025 (38 estudos incluídos), para checar sobreposição com a matriz já mapeada.

### Estudos novos identificados (não estavam na matriz)

| Estudo | Amostra/Método | Foco | Rad+Path juntos? | Framework sociotécnico? |
|---|---|---|---|---|
| Farič et al. 2023, JAMIA | Entrevistas semiestruturadas + observação, sites early-adopter (Escócia) | Experiências iniciais de integração de DSS de IA (Veye Lung Nodules) | Não (só radiologia) | Não |
| Stogiannos et al. 2025, J Med Imaging Radiat Sci | 5 entrevistas semiestruturadas, profissionais de imagem/radioterapia (UK) | Lições de implementação a partir de práticos sêniores | Não | Não |
| Wenderott et al. 2024, Applied Ergonomics | Entrevistas com radiologistas alemães, IA-CAD para RM de próstata | Barreiras/facilitadores de integração ao workflow | Não | Não SEIPS — usa "Model of Workflow Integration" + TAM |
| Kim et al. 2024, Insights into Imaging | Estudo de caso etnográfico longitudinal (3 anos), 18 entrevistas + 43 dias de observação, centro acadêmico holandês | Abordagem "holística" para implementação de IA | Não | Adjacente a sociotécnica, mas não SEIPS explícito |

Nenhum dos 4 estudos novos combina radiologistas e patologistas na mesma amostra; nenhum usa SEIPS 2.0 explicitamente em nível de estudo primário.

### Achado importante sobre os 38 estudos de Wenderott et al. 2025

Todos os 38 estudos incluídos na revisão são quantitativos/observacionais (tempos de leitura, taxas de detecção, validações retro/prospectivas) — **nenhum é estudo qualitativo de experiência**. Apenas um envolve patologia (Sandbank et al. — validação de IA em patologia mamária, 5.954 casos, puramente quantitativo). O SEIPS é usado pelos próprios revisores como lente de síntese pós-hoc para codificar barreiras/facilitadores extraídos de estudos quantitativos — **não está presente nos estudos primários como lente de coleta qualitativa**. Isso é uma distinção importante: confirma que SEIPS já circula no campo como ferramenta analítica de revisão, mas ninguém ainda o aplicou como lente etnográfica/qualitativa primária em radiologia+patologia — exatamente o espaço da proposta de Thiago.

### Duplicata confirmada
"Naicker et al., JMIR 2026, e80342" (NASSS, 43 entrevistas, Brisbane) é o mesmo estudo já mapeado como #3 da matriz original — não é um achado novo.

### Limitações desta busca
- Das 14 "experience studies" de Lawrence et al., só foi possível identificar com segurança ~12 via texto corrido (a Tabela 1 do artigo é resumo numérico, sem lista nominal completa); apêndices suplementares (.docx) não foram baixados/parseados.
- Sem acesso a full-text pago de estudos individuais além de abstracts.

### Leitura atualizada do gap (após rastreamento das fontes)

Mesmo garimpando diretamente os estudos-fonte das duas revisões-guarda-chuva mais recentes (2025), **nenhum estudo qualitativo primário combina radiologistas e patologistas na mesma amostra**, e **nenhum aplica SEIPS 2.0 explicitamente como framework de coleta/análise em nível de estudo primário** sobre experiência de uso de IA diagnóstica — apenas como ferramenta de síntese pós-hoc de revisor (Wenderott 2025). Isso é a terceira confirmação independente (após Lawrence 2025 e Wenderott 2025) de que o gap da proposta de Thiago permanece válido e agora tem evidência ainda mais granular (nível de estudo individual, não só de revisão) para citar no Background.

**Matriz de literatura agora totaliza 10 estudos mapeados** (6 da sessão 25/07 + 4 novos desta sessão), todos catalogados sem sobreposição.

---

## Apêndices suplementares baixados via Europe PMC API (04/08/2026, sessão noturna)

Continuação do item 6 dos "Próximos passos" (sessão 03/08): os sites originais (Lancet/eClinicalMedicine e PMC) bloqueiam WebFetch/agent-browser com Cloudflare + prova-de-trabalho JS/reCAPTCHA. Contornado via **API REST da Europe PMC** (`ebi.ac.uk/europepmc/webservices/rest/{PMCID}/supplementaryFiles` e `/fullTextXML`), sem essas proteções. Baixados e lidos: planilha completa dos 140 estudos de Lawrence et al. (mmc1.xlsx, coluna nominal "Study topic") + apêndices S1-S7 (quality assessment); os 9 Multimedia Appendices (docx) de Wenderott et al. + full-text XML com a Tabela 1 nominal dos 38 estudos. Arquivos salvos em `attachments/lawrence_supp/` e `attachments/wenderott_supp/` (xlsx/docx/XML + script `parse_xlsx.py`).

### Lista nominal completa das 14 "Experience studies" de Lawrence et al. 2025

Os 2 que faltavam identificar (de 12/14 já mapeados em 03/08): **Rosa et al. 2023** (Eur J Radiol Open) e **Liu et al. 2024** (J Clin Imaging Sci, radiologistas na China, nódulo pulmonar). Lista completa: Carlile 2020, Choi 2023, ESR 2022, Faric 2023, Hoppe 2024, Liu 2024, Nehme 2023, Rabinovich 2022, Rosa 2023, Shiang 2022, Shin 2023, Stogiannos 2025, Wenderott 2024, Yoon 2023 — **todas radiologia, nenhuma patologia**. Confirma que a categoria "experience" de Lawrence et al. é 100% radiologia, reforçando o argumento de diferenciação (proposta de Thiago cobre radiologia+patologia).

### ⭐ Achado crítico — precedente publicado mais próximo do gap de Thiago

**Drogt J, Milota M, Veldhuis W, Vos S, Jongsma K (2024). "The promise of AI for image-driven medicine: qualitative interview study of radiologists' and pathologists' perspectives." JMIR Human Factors. 11:e52514.**

- 21 entrevistas (7 patologistas, 10 radiologistas, 4 cientistas de computação), Holanda — **combina radiologistas E patologistas na mesma amostra qualitativa**, exatamente a combinação da proposta de Thiago.
- Já estava na matriz original (item #2, mapeado em 25/07) — mas o motivo de não ter aparecido no rastreamento de fontes de 03/08 agora está claro: **Lawrence et al. o classificou como "Perceptions", não "Experience"** — por isso não estava nos 14 estudos-fonte rastreados naquela sessão. É o mesmo estudo, confirmado via full-text.
- **Boa notícia para o gap:** confirmado no full-text que o estudo **não usa SEIPS nem qualquer framework sociotécnico** (nenhuma menção). Não invalida o gap de Thiago, mas é o **precedente publicado mais próximo** e deve ser citado e diferenciado explicitamente no Background (mesma população, lente teórica diferente/ausente).

### Achado secundário — patologia dentro dos 38 estudos de Wenderott

**Sandbank et al. 2022** (NPJ Breast Cancer, estudo #92 dos 38 de Wenderott et al. 2025) é validação de IA para detecção de câncer de mama em **biópsias** — ou seja, um dos 38 estudos é de **patologia digital**, não só radiologia/gastro como presumido. É quantitativo/retrospectivo (não qualitativo) — não muda o gap, mas corrige a suposição de que os 38 eram só radiologia.

### ⚠️ Alerta terminológico — SEIPS 2.0 vs SEIPS 3.0

Wenderott et al. 2025 usa explicitamente o modelo **SEIPS como lente de síntese**, mas citam a versão **SEIPS 3.0** (Carayon, Wooldridge & Hoonakker, 2020) — não "2.0" — e consideraram e descartaram CFIR e NASSS como alternativas. **Vale Thiago verificar com Carrigan se a proposta deveria adotar SEIPS 3.0** (versão mais recente, já sendo citada como referência corrente na literatura de 2025) em vez de "2.0" — decisão que cabe a Thiago/Carrigan, não a mim.

### Não verificado
Texto completo de **Wenderott et al. 2024** (Applied Ergonomics, DOI 10.1016/j.apergo.2024.104243 — o estudo primário qualitativo de radiologistas alemães dentro dos 14 de Lawrence) está em periódico Elsevier separado, não baixado nesta sessão — recomenda-se leitura direta para confirmar se usa linguagem SEIPS explícita.

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
2. Ao escrever o Background da proposta (Fase 2A do plano original), usar **Lawrence et al. 2025 e Wenderott et al. 2025** juntas como as duas citações-âncora para "o que já existe" (ambas 2025, ambas em imaging médico, ambas confirmando por ângulos diferentes que a experiência do clínico é sub-representada) e os achados #2-#6 da matriz original como evidência da natureza fragmentada da literatura qualitativa existente
3. Considerar registrar o protocolo no **PROSPERO** em vez de (ou além de) OSF, já que é o registro usado pela revisão mais próxima do campo (Lawrence et al. 2025)
4. ✅ Feito em 03/08/2026: rastreamento direto das fontes de Wenderott et al. 2025 (38 estudos) e Lawrence et al. 2025 (14 estudos de "experiência") — 4 estudos novos mapeados, sem sobreposição com a matriz. Ver seção "Rastreamento das fontes das revisões-guarda-chuva" acima.
5. PsycINFO, Web of Science e CINAHL seguem pendentes de acesso institucional USyd (sem mudança)
6. ✅ Feito em 04/08/2026: apêndices suplementares de ambas as revisões baixados via API da Europe PMC (contornando bloqueio Cloudflare dos sites originais) — lista nominal completa das 14 "experience studies" de Lawrence obtida. Achado crítico: Drogt et al. 2024 (JMIR Human Factors) é o precedente publicado mais próximo do gap (radiologistas+patologistas juntos, mas sem SEIPS) — já estava mapeado, mas agora com origem/classificação esclarecida. Ver seção "Apêndices suplementares baixados via Europe PMC API" acima.
7. **Thiago decidir**: verificar com Carrigan se a proposta deveria adotar **SEIPS 3.0** (versão citada por Wenderott et al. 2025) em vez de "SEIPS 2.0" — ver alerta terminológico na seção acima.
8. Pendente: ler texto completo de Wenderott et al. 2024 (Applied Ergonomics, acesso pago) para confirmar se usa linguagem SEIPS explícita

---

*Arquivo de pesquisa — escrito livremente por Andy (autonomia de pesquisa, ver `preferences.md`). Não decide posicionamento final do Thiago; é matéria-prima para a Fase 2 (escrita do summary), que segue exigindo confirmação/revisão dele antes de qualquer envio à Carrigan.*
