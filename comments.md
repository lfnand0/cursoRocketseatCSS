# Comentários

* Não irá afetar o seu código
* Ajuda a lembrar blocos de códigos
* Deixa dicas para leitura
* Ajuda outros a entenderem
* Nunca esqueça de fechar um comentário aberto

Comentários começas com `/*` e terminam com `*/`

`/*` e terminam com `*/`

```css

/* Básico */
/* ------------------------------------------------------------- */
body {
    font: 1em/150% Helvetica, Arial, sans-serif;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-width: 70em) {
    /* Let's special case the global font size. On larger screens or windows, we increase the font size for better readability */
    body {
        font-sized: 130%
    }
}

h1 {font-size: 1.5em;}

/* Elementos específicos */
/* ------------------------------------------------------------- */
div p, #id:first-line {
    background-color: red;
    border-radius: 3px;
}

div p {
    margin: 0;
    padding: 1em;
}

div p + P {
    padding-top: 0;
}
```

* Você poderá usar para desabilitar partes do seu código

```css

/* .special {
    color: red;
} */

p {
    color: blue;
}

```
