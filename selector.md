# Selectors

Conecta um elemento HTML com o CSS

## Tipos

* Global selector `*`
* Element/Type selector `h1, h2, p, div`
* ID Selector `#box, #container`
* Class Selector `.red, .m-4`
* Attribute Selector, Pseudo-class, Pseudo-element, e outros

<!-- CÓDIGO EM HTML -->
<div id="container" class="m-40">
  <h1>Título2</h1>
  <h2>Subtítulo</h2>
</div>

<!-- CÓDIGO EM CSS -->
* {
  margin: 0;
}

#container {
  width: 240px;
}

.m-40 {
  margin: 40px;
}

h1, h2 {
  color: gray;
  font-size: 60px;
  background: black;
}