### element selector

css selector, seleciona no html o que vai ser mostrado nas tags do html
h1 {
color:blue
}

aplica para todos os elementos com aquela tag

### class selector

.red-text {
color:red
}
uma classe é um atributo que da para adicionar nas tags

<h2 class="red-text">Red</h2>

### id selector

usa a # para definir
#main {
color:red
}

### Diferenças entre ID e Class

Id aplica a apenas UM elemento em cada pagina html, já a classe pode ser aplicado a N elementos

### Atribute Selector

p[dragable]{
color:red
}

<p draggable="true">Drag me </p>
<p draggable="false"> Dont drag me </p>
<p draggable="false"> Dont drag me </p>

"seleciona todos os elementos "dragable" e aplique a cor vermelha"

### Universal selector

é marcado por um asterisco
aplica em tudo da pagina.

\*{
color:red
}
