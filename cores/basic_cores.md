# Cores

Usamos CSS para alterar núcleos do nosso documento.

## Tipos

* cor de fundo (para caixas)
* cor (para textos)
* cor de borda (para caixas)
* outros
  
## Valores

Podemos definir valores por:

* palavra-chave (azul, transparente)
* hexadecimal (#990011)
* funções: rgb, rgba, hsl, hsla

### RGB

* RGB → Vermelho, Verde e Azul
* O alfa representa a transparência do cor
  
``` css
/*<rgb()> values */
color: rgb(34, 12, 64, 0.6) /* 0-255 */
color: rgba(34, 12, 64, 0.6)
```

### Cores globais

Vamos ver sobre os valores globais da propriedade.color

```css
/* Global values */
color: inheritr; /* Herda a cor do elemento anterior */
color: initial; /* Volta a sua cor inicial */
color: unset; /* Pega a cor do contexto */
```

## Refêrencias:

[https://developer.mozilla.org/en-US/docs/Web/CSS/color_value]