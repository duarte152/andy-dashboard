# Plano de Ação — MPhil USyd / Proposta para Dr. Carrigan
*Criado por Andy em 17/06/2026 | Atualizar conforme progresso*

---

## OVERVIEW EXECUTIVO

A Dr. Carrigan pediu um **summary de 2-3 páginas** com 7 elementos, seguindo Vancouver citation style. Esse documento é o deliverable mais importante da candidatura — é o primeiro produto de trabalho que ela vai avaliar. Se for bom, ela vai endossar a candidatura internamente.

**Tema proposto por ela:** Experiências qualitativas de diagnosticistas (radiologistas/patologistas) usando ferramentas de IA de suporte diagnóstico — sob uma lente de human factors/sociotechnical systems.

**Metodologia:** Scoping review (não pesquisa primária — factível para MPhil de 1-2 anos).

**Prazo recomendado:** Enviar o summary até **5 de julho de 2026**.

---

## FASES DO PLANO

### FASE 0 — Preparação (17–18 Jun) ✅ PRIORITÁRIA

#### 0.1 Ler o scoping review da Carrigan (URGENTE)
O arquivo `SEIPS review_final_App Erg.docx` está salvo em `/workspace/group/attachments/`.
Notas detalhadas de leitura em: `carrigan_scoping_review_notes.md`

**O que o review é sobre:** Aplicação do framework SEIPS a Digital Health Interventions — mapeia como o SEIPS é usado em design, implementação e avaliação de tecnologias de saúde digital. 24 artigos incluídos, de 676 identificados.

**O que copiar para a proposta de Thiago:**
- Framework: JBI methodology for scoping reviews
- Databases: Medline (via PubMed), PsycINFO, Web of Science, CINAHL
- Registrar protocolo no OSF antes de começar
- Ferramenta de screening: Covidence ou Rayyan (gratuitos)
- Extração de dados: planilha Excel simples

**O que NÃO copiar:** A escala (6 revisores, 676 resultados) — para MPhil solo, o processo é simplificado mas segue a mesma estrutura.

**Prioridade de leitura:** Introduction (como ela constrói o gap) + Methods 2.1-2.2 (estrutura de busca) + Conclusions (estilo de projetar trabalho futuro).

**Por quê:** Ela disse "you don't need this level of detail for the proposal" — o review é o teto de qualidade. A proposta deve ser mais simples, no mesmo registro intelectual.

#### 0.2 Instalar Zotero
- Baixar em zotero.org (gratuito)
- Instalar o browser connector (Chrome/Firefox)
- Instalar o plugin Word ou Google Docs
- Configurar o citation style como "Vancouver"

**Por quê:** Gerenciar 30-50 referências manualmente é impraticável. Zotero insere as citações Vancouver automaticamente.

#### 0.3 Abrir conta no PubMed
- Criar uma conta gratuita em pubmed.ncbi.nlm.nih.gov
- Permite salvar buscas e exportar resultados direto para o Zotero

---

### FASE 1 — Revisão de Literatura (19–27 Jun)

Esta fase tem 3 sub-etapas:

#### 1A — Busca nas bases de dados (19–23 Jun)

Fazer buscas sistemáticas nas seguintes bases, nessa ordem de prioridade:

**MESMAS 4 BASES que a Carrigan usou no review dela:**

**1. Medline via PubMed (principal — gratuito)**
- URL: pubmed.ncbi.nlm.nih.gov
- Usar MeSH terms + keywords:
  - `("Radiology"[MeSH] OR "Pathology"[MeSH] OR "Diagnostic Imaging"[MeSH]) AND ("Artificial Intelligence"[MeSH] OR "Clinical Decision Support Systems"[MeSH]) AND ("Qualitative Research"[MeSH] OR "Attitude of Health Personnel"[MeSH])`
  - `("radiologist" OR "pathologist" OR "diagnostician") AND ("AI" OR "artificial intelligence") AND ("experience" OR "perception" OR "adoption" OR "human factors")`

**2. PsycINFO (comportamento e fatores humanos)**
- Acesso via APA PsycNet ou Ovid (USyd dará acesso após matrícula)
- Termos: `("clinician" OR "radiologist") AND ("artificial intelligence" OR "machine learning") AND ("attitude" OR "perception" OR "user experience")`

**3. Web of Science**
- Acesso institucional USyd
- Útil para capturar literatura interdisciplinar (Computer Science + Medicine)

**4. CINAHL (Nursing & Allied Health)**
- Acesso via EBSCOhost — USyd
- `"AI" AND ("clinical workflow" OR "work system") AND ("clinician experience" OR "usability")`

*Nota:* Para agora (pré-matrícula), fazer a busca piloto no PubMed/Medline. As outras 3 bases serão acessadas via biblioteca da USyd. Mencionar isso na seção Methods da proposta.

**Ferramenta de screening:** Usar **Rayyan** (rayyan.ai — gratuito) ou **Covidence** para triagem de títulos/abstracts, como a Carrigan fez com Covidence.

**O que anotar:**
Para cada paper relevante encontrado:
- Salvar no Zotero (1 clique com o browser connector)
- Categorizar: Quantitativo / Qualitativo / Mixed / Review
- Anotar se foca em: performance técnica (acurácia/sensibilidade) OR experiência humana (percepção, adoção, workflow)

#### 1B — Análise e mapeamento do gap (24–25 Jun)

Depois de coletar os papers, fazer uma análise simples:

**Tabela de categorização:**
| Categoria | Nº de papers | % do total |
|-----------|-------------|------------|
| Foco em acurácia/performance técnica | ?? | ?? |
| Foco em experiência humana/qualitativo | ?? | ?? |
| Mixed | ?? | ?? |

O objetivo é documentar quantitativamente que a maioria dos estudos foca em métricas técnicas, não na experiência humana. Esse é o gap.

**Os poucos estudos qualitativos que existirem são valiosos:**
- Se encontrar 5-10 estudos qualitativos sobre experiência de radiologistas/patologistas com IA — ótimo. Eles mostram que o gap existe mas não foi suficientemente explorado.
- Se encontrar menos de 5 — o gap é ainda mais forte.

#### 1C — Identificar frameworks teóricos (26–27 Jun)

A Carrigan trabalha com human factors/sociotechnical lens. Os principais frameworks dessa área:

**SEIPS 2.0 (Systems Engineering Initiative for Patient Safety)**
- Carayon et al. (2006, atualizado 2020)
- Analisa: Person + Tasks + Tools/Technology + Physical environment + Organizational conditions
- O mais citado em saúde digital e human factors clínicos

**Sociotechnical Systems Theory**
- Trist & Bamforth (origem), adaptado para saúde
- Foco na interação entre dimensões social e técnica

**Technology Acceptance Model (TAM)**
- Davis (1989)
- Foco em perceived usefulness e ease of use
- Muito citado em adoção de tecnologia clínica

**Recomendação:** Usar SEIPS como framework primário — é o mais alinhado ao grupo da Carrigan. Mencionar na seção Method.

---

### FASE 2 — Escrita do Summary (28 Jun – 3 Jul)

Documento final: 2-3 páginas, Fonte 11pt, espaçamento 1.5, margens padrão.
**Seguir EXATAMENTE a estrutura que ela pediu.**

#### 2A — Background (28–29 Jun)

*O que escrever:*
1. Parágrafo 1 — Crescimento de ferramentas de IA diagnóstica: contextualizar o crescimento de IA em radiologia e patologia. Citar 3-4 papers sobre penetração de mercado, crescimento de sistemas de IA, etc.

2. Parágrafo 2 — O que a literatura atual foca: "The predominant body of literature evaluates AI diagnostic tools through a technical performance lens — sensitivity, specificity, area under the curve (AUC), and diagnostic accuracy." Citar 3-4 reviews ou meta-analyses que confiram isso.

3. Parágrafo 3 — Human factors e sociotechnical systems: introduzir a perspectiva alternativa. Mencionar SEIPS, citar 2-3 papers sobre human factors em saúde digital. "Despite this growing evidence base on technical performance, the human experience of using these tools remains underexplored."

*Citações Vancouver:* Numerar sequencialmente conforme aparecem. Ex: [1], [2,3], [4-6].

*Tom:* Factual, sem julgamentos. A voz de quem mapeou a literatura, não de quem tem uma tese a defender.

#### 2B — Problem (30 Jun)

1 parágrafo de 3-4 frases. Deve ser cirúrgico.

*Rascunho sugerido:*
> "Despite a growing body of evidence on the technical performance of AI diagnostic support tools, there is a notable absence of research examining the lived experiences of diagnosticians who use these tools in their clinical workflow. Existing literature predominantly evaluates sensitivity, specificity, and accuracy, but does not address how AI tools are experienced from a human factors and sociotechnical perspective. This gap is significant: technology adoption in clinical settings is shaped not only by technical performance, but by workflow integration, trust, cognitive load, and the human-technology interaction — factors that cannot be captured by performance metrics alone. [citations]"

#### 2C — Aims (30 Jun)

3 bullet points claros e paralelos:

> *This review aims to:*
> 1. *Systematically map existing literature on diagnosticians' experiences of using AI support tools in clinical practice;*
> 2. *Identify key themes, gaps, and inconsistencies in the evidence base regarding human factors in AI-assisted diagnosis;*
> 3. *Provide a research agenda for future qualitative investigations into diagnostician-AI interaction.*

#### 2D — Method (1 Jul)

*O que incluir:*
- Tipo de review: **Scoping review** seguindo o framework JBI (Joanna Briggs Institute)
- Guidelines de reporte: **PRISMA-ScR** (PRISMA for Scoping Reviews)
- Bases de dados: PubMed, Scopus, CINAHL, Google Scholar
- Termos de busca: listar os principais (pode copiar da Fase 1)
- Critérios de inclusão: estudos qualitativos ou mixed-methods; radiologistas, patologistas ou outros diagnosticistas; ferramentas de IA diagnóstica; qualquer data de publicação; inglês
- Critérios de exclusão: estudos focados apenas em performance técnica; não clínicos; não relacionados a diagnosticistas
- Processo de screening: título/abstract → texto completo
- Framework de análise: SEIPS 2.0 para categorização temática dos achados

*Não precisa de muita profundidade aqui* — ela disse que não quer o nível de detalhe do review dela.

#### 2E — Expected Outcomes and Benefits (1 Jul)

1 parágrafo curto:

> "This review will produce a thematic map of diagnosticians' reported experiences with AI support tools, identifying patterns, gaps, and inconsistencies in the current evidence base. Findings will inform both future qualitative research designs and practical recommendations for the implementation of AI diagnostic tools in clinical settings. The review will also contribute to the emerging literature on human factors in digital health, with direct relevance to real-world deployment contexts."

#### 2F — Next Steps (2 Jul)

3 bullets:
> - Register the scoping review protocol on Open Science Framework (OSF)
> - Conduct pilot search and refine inclusion/exclusion criteria with supervisor
> - Proceed with formal MPhil application to the University of Sydney

#### 2G — References (2–3 Jul)

- Gerar a lista completa do Zotero em Vancouver style
- Verificar: até 6 autores por entrada; abreviação correta dos journals; ano, volume, páginas no formato correto
- Numeração sequencial conforme ordem de aparição no texto

---

### FASE 3 — Revisão e Envio (4–5 Jul)

#### 3A — Revisão com olhos frescos (4 Jul)

*Checklist de revisão:*
- [ ] Tem exatamente os 7 elementos pedidos pela Carrigan?
- [ ] Nenhum em dash (—) — apenas hífen simples (-)
- [ ] Todas as afirmações do Background têm citação?
- [ ] O gap está articulado claramente em 1 parágrafo?
- [ ] Os Aims respondem diretamente ao gap?
- [ ] O Method é factível para um MPhil sozinho em 1-2 anos?
- [ ] Vancouver style consistente em todo o documento?
- [ ] 2-3 páginas (não mais, não menos)?
- [ ] Leu em voz alta para verificar clareza?

#### 3B — Enviar para a Carrigan (5 Jul)

Email de envio deve ser curto e profissional:
> *Dear Dr. Carrigan,*
> *Please find attached the initial summary we discussed. I have focused on the human factors/sociotechnical experiences of diagnosticians using AI support tools, as we agreed. I look forward to your feedback on the direction and scope.*
> *Best, Thiago*

---

### FASE 4 — Pós-aprovação da proposta (Jul em diante)

*Aguardando resposta da Carrigan sobre o summary:*

#### 4A — Ajustes baseados no feedback da Carrigan

Ela provavelmente vai pedir ajustes. Isso é normal e saudável. Responder com agilidade — não deixar passar mais de 48h para implementar o feedback.

#### 4B — Aplicação formal (estimativa: agosto 2026)

Processo de aplicação formal ao MPhil na USyd:
1. Criar conta no sistema de aplicação da USyd (Sydney Student Online)
2. Submeter: transcripts, TCC, English proficiency (IELTS 8.0 — já tem), 2 referências, SoP, research proposal
3. A Carrigan vai precisar formalmente aceitar supervisão no sistema
4. A faculdade avalia a equivalência do TCC ao Honours

*Documentos a preparar:*
- [ ] Transcript oficial da PUC-Rio (autenticado e traduzido para inglês)
- [ ] TCC em inglês (tradução já feita)
- [ ] IELTS score report (já tem — 8.0)
- [ ] 2 cartas de recomendação (acadêmica + profissional)
- [ ] Statement of Purpose (atualizar o existente para focar no projeto com Carrigan)
- [ ] Research proposal final (output da Fase 2)

#### 4C — RTP (Research Training Program) Scholarship

O RTP é a principal bolsa para alunos internacionais em programas de pesquisa australianos. Cobre taxa de matrícula + stipend (~AUD 33k/ano).

- Deadlines típicos: julho-agosto para início em fevereiro do ano seguinte
- Verificar no site da USyd: sydney.edu.au/scholarships/research
- A candidatura ao RTP é vinculada à candidatura ao programa — não é separada

---

## CRONOGRAMA RESUMIDO

| Período | Fase | Entregável |
|---------|------|-----------|
| 17-18 Jun | Fase 0 | Leu scoping review da Carrigan + Zotero instalado |
| 19-23 Jun | Fase 1A | Buscas nas 4 bases de dados concluídas |
| 24-25 Jun | Fase 1B | Gap mapeado, papers categorizados |
| 26-27 Jun | Fase 1C | Framework teórico definido (SEIPS) |
| 28-29 Jun | Fase 2A | Background escrito + citado |
| 30 Jun | Fase 2B-C | Problem + Aims escritos |
| 1 Jul | Fase 2D-E | Method + Expected Outcomes escritos |
| 2-3 Jul | Fase 2F-G | Next Steps + References completos |
| 4 Jul | Fase 3A | Revisão final |
| 5 Jul | Fase 3B | Envio para a Carrigan |
| Jul+ | Fase 4 | Ajustes + Aplicação formal |

---

## CONEXÃO DA LAUDITE COM O PROJETO

Usar no Background/Aims para contextualizar motivação (sem tornar a Laudite o objeto de estudo):

> *"My professional background as Product Enablement Lead at Laudite, a generative AI platform for medical reporting operating with radiologists, pathologists, and endoscopists across Brazil, has provided direct observation of the human factors challenges involved in AI adoption in clinical diagnostics. This practitioner perspective motivates the proposed research into the underexplored qualitative dimensions of diagnostician-AI interaction."*

**Importante:** A Laudite não é uma ferramenta de "AI diagnostic support" no sentido estrito — ela gera laudos, não recomenda diagnósticos. Ser honesto sobre isso na proposta, mas mostrar como a experiência de observar clinicistas interagindo com IA em fluxos de documentação clínica dá insight sobre a dinâmica humano-tecnologia relevante para o campo mais amplo.

---

## DICIONÁRIO RÁPIDO (termos que vão aparecer)

| Termo | Significado |
|-------|-----------|
| **Scoping review** | Revisão de literatura que mapeia o território de um campo — extensão, natureza e distribuição da evidência. Não avalia qualidade dos estudos. |
| **Systematic review** | Revisão mais rigorosa que responde a uma pergunta clínica específica e avalia qualidade dos estudos. Mais demorada. |
| **PRISMA-ScR** | Preferred Reporting Items for Systematic Reviews and Meta-Analyses extension for Scoping Reviews — guideline de como reportar o processo |
| **JBI** | Joanna Briggs Institute — referência em metodologia de reviews em saúde |
| **SEIPS** | Systems Engineering Initiative for Patient Safety — framework de análise de sistemas de trabalho em saúde |
| **HDR** | Higher Degree Research — categoria que inclui MPhil e PhD na Austrália |
| **RTP** | Research Training Program — principal bolsa federal australiana para HDR |
| **Vancouver style** | Sistema de citação numerado (não autor-data), padrão em medicina |
| **OSF** | Open Science Framework — plataforma para registro de protocolos de pesquisa |
| **Grey literature** | Literatura não publicada em journals: relatórios, teses, preprints, documentos governamentais |

---

*Arquivo criado por Andy — 17/06/2026*
*Próxima atualização: após leitura do scoping review da Carrigan*
