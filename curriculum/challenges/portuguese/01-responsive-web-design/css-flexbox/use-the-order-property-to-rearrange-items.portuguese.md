{
    "shape":[2,768],
      "data":[
          [0.03190416097640991, 0.006062490865588188, 0.025968171656131744,...],
              [0.002439928939566016, -0.021352028474211693, 0.06229676678776741,...],
                  [-0.02154572866857052,0.09098546206951141,0.006273532286286354,...]
                    ]
                    }---
id: 587d78ae367417b2b2512aff
title: Use the order Property to Rearrange Items
challengeType: 0
videoUrl: ''
localeTitle: ''
---

## Description
<section id="description"> A propriedade <code>order</code> é usada para informar ao CSS a ordem de como os itens flexíveis aparecem no contêiner flexível. Por padrão, os itens aparecerão na mesma ordem em que aparecem no HTML de origem. A propriedade aceita números como valores e números negativos podem ser usados. </section>

## Instructions
<section id="instructions"> Adicione o <code>order</code> propriedade CSS aos dois <code>#box-1</code> e <code>#box-2</code> . Dê <code>#box-1</code> um valor de 2 e dê <code>#box-2</code> um valor de 1. </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: 'O elemento <code>#box-1</code> deve ter a propriedade <code>order</code> configurada para um valor de 2.'
    testString: 'assert($("#box-1").css("order") == "2", "The <code>#box-1</code> element should have the <code>order</code> property set to a value of 2.");'
  - text: 'O elemento <code>#box-2</code> deve ter a propriedade <code>order</code> configurada para um valor de 1.'
    testString: 'assert($("#box-2").css("order") == "1", "The <code>#box-2</code> element should have the <code>order</code> property set to a value of 1.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;

    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;

    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
