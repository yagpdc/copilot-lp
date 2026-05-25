# lp-copilot

Apresentação cinematográfica do **Driva Copilot** — a IA comercial que prospecta, investiga e age sobre toda a base de empresas do Brasil, direto no WhatsApp.

Não é uma landing page convencional: é uma experiência em scroll, em atos, no estilo de sites como Kudanil, The Art of Cinema e Equator.

## Como ver

É um único arquivo estático, sem build. Basta abrir `index.html` no navegador, ou servir localmente:

```bash
python -m http.server 4321
# abra http://localhost:4321
```

## Estrutura

- `index.html` — tudo (HTML + CSS + JS inline). Auto-contido.
- `.claude/launch.json` — config de preview local (opcional).

## Notas técnicas

- **Tipografia:** Syne (display) + Inter (corpo) + Space Grotesk (mono), via Google Fonts.
- **Paleta:** roxo, rosa, laranja e azul claro sobre fundo quase preto, com grão de filme e vinheta.
- **Atos:** loader → hook → tensão → virada → o produto ao vivo (mock WhatsApp) → montagem horizontal das 16 capacidades → números → finale.
- **Smooth scroll** via Lenis (carregado de forma assíncrona; cai para scroll nativo se indisponível).
- **Sem dependências de build.** Pronto para GitHub Pages.

## Deploy (GitHub Pages)

Em *Settings → Pages*, selecione a branch `main` e a pasta `/ (root)`.
