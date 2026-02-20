# Brand Toolkit — Kit de Desenvolvimento de Marca

> Kit reutilizavel para iniciar projetos de branding com processo profissional de 6 fases.
> Desenvolvido a partir do projeto real MaikMello (2026).

---

## Para Quem Serve

- Empreendedores que precisam criar uma marca do zero
- Designers e estrategistas de marca
- Qualquer pessoa que queira seguir um processo profissional de branding com auxilio de IA

---

## Como Usar

### 1. Copie a pasta
Duplique a pasta `Brand_Toolkit/` para um novo projeto. Renomeie como quiser (ex: `NomeDaMarca_Branding/`).

### 2. Inicie uma sessao com o Claude
Copie o conteudo de `PROMPT_INICIAL.md` e cole no inicio de uma conversa com o Claude. Isso configura o Claude como Brand Strategist e referencia todos os arquivos do kit.

### 3. Siga as 6 fases
O processo e sequencial — cada fase gera insumos para a proxima:

| Fase | Nome | O Que Acontece |
|------|------|----------------|
| 0 | **Intake** | Briefing com o cliente — perguntas sobre fundador, negocio, publico, percepcoes |
| 1 | **Discovery** | Pesquisa competitiva, mapa de posicionamento, personas detalhadas |
| 2 | **Strategy** | Plataforma de marca (proposito, missao, arquetipos, tom de voz, naming) |
| 3 | **Creative Direction** | Moodboard, paleta de cores, tipografia, direcao visual |
| 4 | **Visual Identity** | Logo, elementos de suporte, motion/animacao, mockups |
| 5 | **Brand Book & Launch** | Documentacao final, biblioteca de assets, templates prontos |

### 4. Preencha o Brand Studio
O Claude criara o `BRAND_STUDIO.md` do seu projeto a partir do template (`03_Templates/BRAND_STUDIO_TEMPLATE.md`). Este arquivo e o documento vivo do projeto — todas as decisoes ficam registradas nele.

---

## Estrutura dos Arquivos

```
Brand_Toolkit/
│
├── LEIA-ME.md                              ← Voce esta aqui
├── PROMPT_INICIAL.md                       ← Prompt para iniciar sessao com Claude
│
├── 01_Metodologia/
│   ├── branding-masterclass.md             ← Processo completo (frameworks, KPIs)
│   └── brand-development-masterclass.md    ← Fases detalhadas (Wolff Olins, Landor)
│
├── 02_Pesquisa/
│   ├── cores_e_psicologia.md               ← Teoria de cores, 60-30-10, WCAG, cultura BR
│   ├── tipografia_logo_identidade.md       ← Tipografia, logo design, grid, golden ratio
│   ├── moodboard_posicionamento.md         ← Moodboards, arquetipos, naming, brand voice
│   ├── marca_pessoal.md                    ← Marca pessoal (PIECES, Ikigai), plataformas
│   ├── estrategia_conteudo.md              ← Content strategy, pilares, SEO, editorial
│   ├── referencias_logo_design.md          ← Logos iconicos, tendencias de design
│   ├── logos_iconicos_educacao.md           ← Logos financeiros/educacionais, premiacoes
│   └── logos_marcas_reais.md               ← Analise de Monzo, Motorola, Miro, Monday etc.
│
├── 03_Templates/
│   ├── worksheets_10_ferramentas.md        ← 10 worksheets prontos (Briefing, Prisma, Persona...)
│   ├── BRAND_STUDIO_TEMPLATE.md            ← Workspace em branco (6 fases, pronto para preencher)
│   └── template_analise_competitiva.md     ← Template de analise competitiva
│
└── 04_Caso_Referencia/
    └── MaikMello_BRAND_STUDIO.md           ← Projeto completo preenchido (exemplo real)
```

---

## Sobre Cada Pasta

### 01_Metodologia/
Dois arquivos densos (~3.000 linhas) com a base teorica do processo. Cobrem frameworks de grandes agencias (Wolff Olins, Landor, Pentagram), KPIs de marca, checklists de entrega por fase. O Claude usa estes como referencia principal.

### 02_Pesquisa/
Oito arquivos de pesquisa (~5.500+ linhas) cobrindo cores, tipografia, logos, moodboards, marca pessoal e estrategia de conteudo. Consultados sob demanda conforme a fase do projeto exigir.

### 03_Templates/
Ferramentas de trabalho:
- **Worksheets**: 10 ferramentas prontas (Brand Briefing, Prisma de Kapferer, Mapa de Persona, Analise SWOT, etc.)
- **Brand Studio Template**: O documento-mestre do projeto, com todas as secoes e perguntas das 6 fases — em branco, pronto para preencher
- **Template de Analise Competitiva**: Estrutura padrao para analisar concorrentes e referencias

### 04_Caso_Referencia/
O projeto MaikMello completo — todas as 6 fases preenchidas, decisoes documentadas, checklists marcados. Serve como exemplo de como um Brand Studio fica quando finalizado.

---

## Dicas de Uso com Claude

1. **Cole o prompt inteiro** — nao resuma. O prompt referencia arquivos especificos e define o processo.
2. **Siga a ordem das fases** — pular etapas gera lacunas que prejudicam as fases seguintes.
3. **O expert conduz, voce decide** — o Claude vai apresentar opcoes fundamentadas. Voce escolhe.
4. **Salve decisoes no Brand Studio** — e o documento vivo. Tudo fica registrado la.
5. **Consulte o caso de referencia** — se tiver duvida de como uma secao deve ficar, olhe o MaikMello.

---

*Kit criado em fev/2026 a partir do projeto de branding MaikMello.*
