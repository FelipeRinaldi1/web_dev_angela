<html style="background:blue">
"background"<-Property
"blue"<-Value

Inline: Css interno, fica apenas no meio do arquivo html. Aplicado a uma linha (Nao recomendado)

<html>
    <head>
        <style>
            html{
                Background:red;
                }
        <style
    <head
<html
Internal: Pode ser aplicado em qualquer parte do site. (não recomendado em sites multi pagina)

<html>
    <head>
        <link
            rel="stylesheet" <-relationship
            href="./styles.css" <-Location
            />
    </head>
</html>
External: As modificações css ficam no arquivo .css (mais usado)
