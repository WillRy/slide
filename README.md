# Slide

Slide feito com CSS/JavaScript puro, tendo duas versões:

- Slide com navegação
- Slide sem navegação

## Utilização

Adicione ao seu site o arquivo slide.js (Slide sem navegação) ou slidenav.js (Slide com navegação) que estão dentro da pasta dist, assim como o arquivo slide.css.

```js
// código para o arquivo /dist/slide.js
// O primeiro seletor .slide, deve ser o elemento que envolve diretamente os slides.
// O segundo seletor deve ser um elemento a parte que envolve o .slide
const slide = new Slide(".slide", ".slide-wrapper");
slide.init();
```

```js
// código para o arquivo /dist/slidenav.js
// O primeiro seletor .slide, deve ser o elemento que envolve diretamente os slides.
// O segundo seletor deve ser um elemento a parte que envolve o .slide
// caso deseje controles acione os métodos addArrow e addControl
const slide = new SlideNav('.slide', '.slide-wrapper');
slide.init();
slide.addArrow('.prev', '.next');
slide.addControl('.custom-controls');
```


## Exemplo

Para desenvolvimento utilize o index.html

Para exemplo de utilização, utilize o arquivo exemplo.html
