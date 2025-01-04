# Propriedades das Fontes

h1 {
color:blue
font-weight:bold
font-size:20px
font-family:sans-serif
}

## Novas Propriedades

h1 {fontsize: 20px}

pixel
1px = 1/96 inchi (0.26mm) de altura e largura

point
1pt = 1/72 inch (.35mm) de altura e largura

1em = 100% of parent
ex:

<body> 20px
<h1>Olá</h1> 1em = 20px <!se fosse 2em = 20px * 2 = 40>
</body>
O "em" se altera de valor de acordo com a tag maior que está inclusa.

1rem = 100% of the root

!!! Recomendado o uso do rem!
O "rem" se altera de valor de acordo com o valor padrão do HTML

### Font Weight

normal bold - **keywords**

lighter bolder - **relative to parent**

number - **100 (lighter) -900(bolder)**

### Font Family

font-family: (typeface,backup generic font type)

nota: sans serif as pontas da fonte são retas Ex: Helvetica
serif as pontas possuem "pézinhos" Ex: Times New Roman

font-family: ("Times New Roman")
nota: quando a fonte tem multiplas palavras no nome, se coloca entre aspas

### Text Align

h1{text-align:center}
