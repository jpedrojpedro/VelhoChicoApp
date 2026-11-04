# Velho Chico: site

Site de divulgação do app Android **Velho Chico**, publicado em
<https://www.velhochico.app.br>.

- `/`: página de divulgação (`index.html`)
- `/privacidade/`: política de privacidade do app (`privacidade/index.html`), a URL informada no Play Console

HTML e CSS puros, sem build, sem JavaScript, sem cookies e sem nada carregado de outros sites (a fonte Roboto fica em `fontes/`).

## Ver localmente

```sh
python3 -m http.server 8000
```

E abra <http://localhost:8000>.

## Quando o app for publicado na Google Play

Em `index.html`, troque:

```html
<body data-publicado="false">
```

por:

```html
<body data-publicado="true">
```

O botão "Em breve na Google Play" some e aparece o selo oficial, já com o link
`https://play.google.com/store/apps/details?id=br.app.velhochico`.

## Licença

Ilustrações, Carranca, capturas e textos: todos os direitos reservados.
Código do site: MIT. Veja [LICENSE](LICENSE).
