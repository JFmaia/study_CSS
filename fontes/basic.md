> A tipografia transmite uma mensagem, por exemplo, quando queremos dar uma ênfase no texto nós podemos escrever o mesmo em negrito.

# Fontes

* Nós podemos transmitir uma mensagem diferente dependendo do estilo que escreve o texto.

Algumas das propriedades de fontes do CSS que podem nos ajudar a transmitir uma mensagem dos textos da página são:

* font-família
* peso fonte
* estilo fonte
* tamanho da fonte

## Família Font

* Tipo de fonte de um elemento
* Lista de fontes e ordem de prioridade
* Incluie *fallback* font

```css
p {
  font-family: "Times New Roman", Times, serif;
}
```

Alguns tipos de fontes:

* serif (com serifa)
* sans (sem serifa)

## Peso da fonte

* Peso da fonte
* Valores: | normal | ousado | mais ousado | mais leve 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900
* Dependendo da família da fonte não conseguimos utilizar todos os pesos de fonte

```css
p {
	font-weight: bold;
}
```

Referência

[https://www.w3.org/TR/css-fonts-3/]


## Estilo de fonte
* É o estilo da fonte
* Valores: | normal | itálico oblíquo
* Os valores que podem ser aplicados dependem da fonte usada

```css
span {
	font-style: italic;
}
```

## Tamanho da fonte

* Tamanho da fonte

```css
p {
	font-size: 18px;
}
```

## Fontes da Web

### Fontes do sistema x Fontes da web

**Fontes do sistema** são as fontes que estão instaladas na máquina do usuário e nem sempre o cliente vai ter instalado as fontes usadas no projeto e isso pode fazer com que os estilos dos textos não sejam aplicados corretamente, mas para resolver esses casos podemos preparar nossas fontes para web ou usar fontes da web.

### Como usar fontes para web?
* @font-face
* @import
* link

### Referência

[https://fonts.google.com/]
[https://css-tricks.com/snippets/css/using-font-face-in-css/]