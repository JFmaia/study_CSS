# O é o preenchimento interno da caixa. `padding`

A propriedade preenchimento pode ser escrito como nos formatos apresentados abaixo:

> padding-top | padding-right | padding-bottom | padding-left

Geralmente usamos uma forma abreviada para escrever o preenchimento. Esse formato segue o sentido horário iniciado por , seguindo para , e .top, right, bottom, left

```css
padding: 12px 16px 10px 4px; /* TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px */
padding: 12px 16px 0; /* TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px */
padding: 8px 16px; /* TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px */
padding: 8px; /* TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px */
```
O preenchimento pode ter *valores (valores)* de *comprimento* (px, em, rem) ou de *porcentagem* (%)

* O preenchimento pode causar diferença na largura de um elemento
* 
obs.: Na aula sobre aprendemos como resolver essa diferença na largura do elemento ``box-xizing`

[https://app.rocketseat.com.br/node/uma-caixa-dentro-da-outra/lesson/box-sizing]