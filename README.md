# Capoeira Kids — Landing Page

Página de vendas estática (HTML/CSS/JS puro, sem build).

## Estrutura

```
index.html      página completa
assets/         imagens (img-01 … img-29)
vercel.json     cache e headers de segurança
```

## Pontos de configuração dentro do `index.html`

- **Links de checkout:** objeto `CHECKOUT` (perto da linha 655).
- **Meta Pixel:** ID `3269172659942050` no `<head>`.
- **Vimeo:** domínio `player.vimeo.com` (preconnect no `<head>`).

## Deploy

Cada push na branch `main` gera um deploy de produção na Vercel.
Branches e Pull Requests geram URLs de preview automaticamente.

Teste local: `npx serve .` ou abra o `index.html` no navegador.
