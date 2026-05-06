# Hexaverso — Site

Site multi-página do RPG Hexaverso, pronto para hospedagem no GitHub Pages.

## Estrutura

```
hexaverso/
├── index.html               # Quick-play guide (rosa)
├── jogadores/index.html     # Para quem vai jogar (lime)
├── mestres/index.html       # Regras e fichas dos mestres (preto)
├── downloads/index.html     # Catálogo de material (creme)
├── pesquisa/index.html      # Área científica + CRIACOM (branco sóbrio)
└── assets/
    ├── css/hexaverso.css    # Design system compartilhado
    ├── images/              # Ilustrações (personagens, medidores, Flik)
    ├── fichas/              # PDFs das fichas (a adicionar)
    ├── manual/              # Manual completo PDF (a adicionar)
    └── arte/                # Arte em alta resolução (a adicionar)
```

## Status

Todas as 5 páginas principais estão construídas e funcionais:

- ✅ **index.html** (quick-play) — porta de entrada, divulgação
- ✅ **jogadores/** — leitura pré-mesa para jogadores
- ✅ **mestres/** — guia prático dos dois mestres
- ✅ **downloads/** — catálogo com placeholders para os PDFs
- ✅ **pesquisa/** — área CRIACOM, referenciais, como citar

### Placeholders a preencher

Alguns textos e links precisam ser atualizados antes de colocar no ar:

**Página de pesquisa:** nome completo do coordenador, lista da equipe, número CAAE do Comitê de Ética, e-mail real do CRIACOM, URL final do site e eventual DOI na seção "Como citar".

**Página de downloads:** todos os arquivos estão marcados como "em breve". Conforme você for finalizando a diagramação, substitua os links por arquivos reais em `assets/fichas/`, `assets/manual/` e `assets/arte/`, e troque a tag `em breve` por `disponível`.

## Como publicar no GitHub Pages

1. Crie um repositório público. Sugestão: `hexaverso`
2. Extraia este ZIP e faça upload do conteúdo para a raiz do repo
3. Settings → Pages → Source → branch `main`, pasta `/ (root)`
4. Site estará em `https://SEU-USUARIO.github.io/hexaverso/` em ~1 min

Para usar como site principal (sem subpasta), nomeie o repo como `SEU-USUARIO.github.io`.

## Design system

- **Paleta:** rosa `#E8499F`, lime `#B8E63C`, preto `#0B0B0B`, creme `#F5E6D0`
- **Tipografia:** Archivo Black (display), Space Mono (técnico), Inter (corpo)
- **Diferenciação por página:** cada seção tem uma cor dominante
  - Quick-play → rosa (alegre, divulgação)
  - Jogadores → lime (convite, leve)
  - Mestres → preto (ferramenta, técnico)
  - Downloads → creme (catálogo, biblioteca)
  - Pesquisa → branco + rosa linha fina (científico, sóbrio)

## Créditos

- Arte: Amanda Galdino
- Pesquisa: Neves Filho et al. / UEL-CNPq
- Processo 408699/2023-0 · Chamada Universal CNPq/MCTI n. 10/2023
- Licença: CC BY 4.0
