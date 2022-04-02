# Comentários

* Não irá afetar o seu código
* Ajudar a lembrar blocos de código
* Deixa dicas para o futuro
* Nunca esqueça de fechar um comentário aberto

Coméntarios começam com `/*` e terminam com `*/`.

```css

/* Básico */
/* ------------------ */
body {
    font: 1em/150% Helvetica, Arial, sans-serif;
    padding: 0 auto;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-width: 70em) {
    body {
        font-size: 130%;
    }
}

h1 {
    font-size: 1.5em;
}

/* Elementos especificos*/

div p, #id:first-line {
    background-color: red;
    border-radius: 3px;
}

div p {
    margin: 0;
    pading: 1em;
}

div p + p {
    padding-top: 0;
}
