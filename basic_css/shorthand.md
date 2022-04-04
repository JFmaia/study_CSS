# Shorthand

* junção de propriedades
* resumido
* legível

```css

{
    /* background properties */
    backgroud-color: #000;
    backgroud-image: url(images/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shorthand */
    background: #000 url(images/bg.gif) no-repeat left top;
}
```

## Detalhes

* Não vou considerar propriedades anteriores, ou seja, caso faça uma taquigrafia, apenas ele será considerado,  quaisquer propriedades anteriores serão substituídas pela taquigrafia.

* Os valores que não são especificados irão assumir o valor padrão.

* Por fim, geralmente, a ordem não descrita não importa, mas, caso haja muitas propriedades com valores semelhantes, poderemos encontrar problemas.