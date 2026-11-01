# Site Progastro Linhares

Landing page estática para GitHub Pages.

```
index.html
assets/fonts/Gotham-{Light,Book,Medium}.woff2
```

Publicar: suba tudo na raiz do repositório → Settings → Pages → Deploy from a branch → `main` / `(root)`.

Fontes: Gotham (hospedada em `assets/fonts`) com fallback Montserrat/Outfit via Google Fonts.
Gotham é fonte comercial — em repositório público, confirme a licença de webfont ou apague `assets/fonts/` (o site passa a usar Montserrat).

Logos: embutidos no próprio `index.html` como `<symbol>` (sem arquivos externos). As cores vêm das variáveis CSS `--logo-verm` e `--logo-cinza`.
