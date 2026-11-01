# Site Progastro Linhares

Landing page estática para GitHub Pages.

```
index.html
privacidade.html
assets/fonts/Gotham-{Light,Book,Medium}.woff2
assets/fonts/Montserrat-{Light,Regular,Medium}.woff2
assets/fonts/Outfit-{Light,Regular,Medium}.woff2
assets/fonts/OFL-Montserrat.txt, OFL-Outfit.txt
```

Publicar: suba tudo na raiz do repositório → Settings → Pages → Deploy from a branch → `main` / `(root)`.

Fontes: todas hospedadas em `assets/fonts` (Gotham → Montserrat → Outfit). O site não faz nenhuma requisição a terceiros. Montserrat e Outfit são SIL Open Font License (licenças incluídas).
Gotham é fonte comercial — em repositório público, confirme a licença de webfont ou apague apenas os três `Gotham-*.woff2` (o site passa a usar Montserrat automaticamente).

Logos: embutidos no próprio `index.html` como `<symbol>` (sem arquivos externos). As cores vêm das variáveis CSS `--logo-verm` e `--logo-cinza`.
