# Tema do GELOS p/ [reveal.js](https://revealjs.com)

## Como instalar

Adicione o pacote como dependência do seu projeto:
```sh
npm install git+https://github.com/gelos-icmc/gelos-revealjs
```

## Como usar

A idéia é usar num projeto com pipeline para fazer bundle de assets (e.g. webpack).

No seu entrypoint:
```js
import 'gelos-revealjs/scss/gelos.scss'
```

Alternativamente, se você não quiser incluir pipeline para compilar `sass` no seu projeto, importe a versão compilada:
```js
import 'gelos-revealjs/dist/gelos.css'
```
