# Border

* São como bordas da caixa

* Documentação do MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/border

* valor: | | <border-style> <border-width> <border-color>

  * estilo: | sólido | pontilhada | tracejada | dupla | groove | cume inset | início
  * largura: <length>
  * cor: <color>
```css
div {
	/* shorthand */
	border-top: solid 2px; /* top | right | bottom | left */

	/* style */
	border: solid;

	/* width <length> | style */
	border: 2px dotted;

	/* style | color */
	border: outset #f33;

	/* width | style | color */
	border: medium dashed green;
}
```

## E o contorno?

* O contorno é muito semelhante à fronteira, mas difere em 4 sentidos:

    * Não modifica o tamanho da caixa, pois não é parte do Modelo Caixa
    * Ser diferente De retangular
    * Não permite ajuste individuais
    * Mais pelo usuário usado agente para acessibilidade