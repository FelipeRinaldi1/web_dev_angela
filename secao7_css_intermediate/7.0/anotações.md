# Cascading Style Sheets

Ordem de prioridade das regras na Hierarquia do CSS, o que da nome as regras do css

position (4) > specificity (3) > Type (2) > Importance (1)

## Position

li {
color:red; (3)
color:blue; (2)
}
{  
color: green (1)
}

blue vai sobrepor o red
e apos isso será substituido pelo verde

## Specificty

li {color:blue;}
.first-class {color:red}
li[draggable] {color:purple;}
#first-id {color: orange}

ordem de especificidade
4)element
3)class
2)atribute
1)id

## Type

<link rel="stylesheet" href="./style.css>
<style> </style>
 (3)external
 (2)internal
 (1)inline

## Importance

color:red; (2)  
color:green !important; (1)
