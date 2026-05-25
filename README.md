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

- **Tipografia:** Bricolage Grotesque (display) + Inter (corpo) + Space Grotesk (mono), via Google Fonts.
- **Identidade Driva:** laranja `#f07f2d` + azul-marinho `#003355` como base, com roxo/rosa como acentos vibrantes, grão de filme e vinheta.
- **Cursor:** a própria logo da Driva — branca no escuro, vira colorida e cresce (com rótulo "Agendar") nos CTAs.
- **Atos:** loader → hook → tensão → virada → demo ao vivo no WhatsApp → grid de capacidades (cada feature como um momento de WhatsApp) → números → finale.
- **Sem build e sem CDN.** Tudo inline em um arquivo; funciona offline. Pronto para GitHub Pages.

## Deploy (GitHub Pages)

Em *Settings → Pages*, selecione a branch `main` e a pasta `/ (root)`.
