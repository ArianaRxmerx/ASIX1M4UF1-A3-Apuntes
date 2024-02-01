# ASIX1M4UF1-A3-Apuntes

## Primer Capítulo: GITHUB

## Segundo Capitulo: MARKDOWN

###### Subtitulo
Este texto está en _cursiva_
Este texto está en *cursiva*
Este texto está en __negrita__
Este texto está en **negrita**

Este texto está en __*negrita y cursiva*__

1. Primera opción de menú
2. Segunda opción de menú
3. Tercera opción de menú

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú 
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

'''

<html>

    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>

'''
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")
[Esto es una imagen tumblr](https://img.wattpad.com/b78a86a1855fed470a4fd72b9328e91cd61e627d/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f776174747061642d6d656469612d736572766963652f53746f7279496d6167652f41563146703467585265623066513d3d2d3435343436323235342e313464396465623763613566343037663431383437333735333431312e6a7067?s=fit&w=720&h=720 "Titulo opcional de la imagen")

|Primera COl.|Segunda Colum.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es |Derceha|134€|
|Estilo Cebra|Girls|Blanco|
|Clase|ASIX|M4|

-[ ]Opción A

-[X]Opción B

-[ ]Opción C 

## Tercer Capitulo: HTML
Para crear un html utilizamos el formato html:5
Para crear comentarios se utiliza <!--Esto es un comentario-->
...
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--Esto es para poder acceder a los iconos-->
    <script src="https://kit.fontawesome.com/96c3222760.js" crossorigin="anonymous"></script>

    <title>Esto es el titulo del documento que se muestra en un browser la</title>

<body> <!--Esto es el contenido del documento-->

    <h1 id= "Titulo">Es un encabezado que a la vez es el titulo de la pagina web. Tambien incluye un identificcador que se relacionará con un enlace.</h1>
    <h3>Esto es el tercer encabezado</h3> 
    <p>Esto es un parafo.</p> 
    <p>Esto es un parrafo<strong>Y esto es la parte importante de un parrafo</strong> <!--Se utiliza strong para poner en negrita-->por eso lo pueden ver en negrita</p> <!--Esto es un parrafo-->
    
<ol> <!--Se utiliza ol para hacer una lista ordenada-->
    <li> primer elemento ordenado</li> <!--Se utiliza li para declarar cada uno de los elementos de una lista.-->
    <li> segundo elemento ordenado</li>
    <li>tercer elemento ordenado</li>
</ol>
    <ul> <!--Se utiliza ul para hacer una lista desordenada -->
        <li>primer elemento desordenado</li>
        <li>segundo elemento desordenado</li>
    </ul>

<i class="fa-brands fa-github fa-bounce" style="color: #ff00a2;"></i> <!--Esto es el icono-->

<a href = "https://www.tiktok.com/es/" alt ="Esto es para comentar sin que se muestre en la pagina web" target ="_blank">Esto es un enlace</a>

<blockquote>Se utiliza para definir una sección que contiene una cita de otro documento</blockquote>


<!--Etiqueta para mostrar una imagen-->
<!--../ o ..// para ubicar la imagen fuera de otra carpeta
    ./ para ubicar la imagen en la misma carpeta-->
<img src = "../XML/imagen1.jpg" alt = "Imagen chica">

<a href="#Titulo">Esto es un enlace de titulo mediante identificador.</a>

<hr><!--Se utiliza para crear una linea horizontal-->

<section><!--se utiliza para definir una sección temática o agrupar contenido relacionado en una página web.-->
<table border="1" ><!--Esto crea una tabla y establece un borde visible alrededor de las celdas de la tabla-->
        <thead> <!--Son s celdas de encabezado de la tabla-->
            <th>Primera celda de encabezado</th>
            <th>Segunda celda de encabezado</th>
            <th>Tercera celda de encabezado</th>
        </thead>
        <tbody><!--Aquí se encuentran las filas y celdas de datos principales de la tabla-->
            <tr><!--representa una fila-->
                <td>Primera celda de datos.</td>
                <td>Segunda celda de datos</td>
                <td>Tercera celda de datos</td>
            </tr>
            <tr>
                <td >Cuarta celda de datos</td>
                <td>Quinta celda de datos</td>
                <td>Sexta celda de datos</td>
            </tr>
        </tbody>
        <tfoot><!--Es el pie de la tabla.-->
            <tr>
                <td><b>Texto en negrita</b></td>
                <td><b>Texto en negrita</b></td>
                <td><b>Texto en negrita</b></td>
            </tr>
        </tfoot>
    </table>
</section>
</body>
</html>
...

## Cuarto Capitulo: CSS
Existen 3 tipos de formato en css:
1. INTERNO:
<html>
/*Se utiliza para incorporar reglas de estilo (CSS) en el mismo documento html en la seccion de head*/
<head>
<style> 
/*Selector universal * selecciona todos los elementos en el documento.*/

* {        
    background-color:DodgerBlue; /*Establecer el color de fondo con el nombre del color*/
    color: RGB(244, 53, 179); /*Establecer el color del texto*/
    border: 1px solid #008000; /* Borde sólido verde */
}

/* Selector de Tipo: Selecciona todos los elementos de un tipo específico.*/
p {
    /* Establecer el ancho del borde en 5 píxeles */
border-width: 5px;
}
/*Selector de clase: permiten seleccionar todos los elementos que tienen un mismo nombre de clase.*/
.button {
    background-color: #4CAF50;
    color: white;
    
}
/*Selector ID: está diseñado para seleccionar elementos con base en su atributo de ID*/
#header {
    
    color: #333;
}
/*Selector de Atributo: Selecciona elementos que tienen un atributo específico.*/

</style>
</head>
</html>

...
2. EN LINEA:
/*Los estilos en línea en CSS se aplican directamente a un elemento HTML utilizando el atributo style*/

<html>
<p style="color: blue;">Cambiar color del texto</p>
<div style="background-color: #f2f2f2; font-size: 16px;">Seleccionar fondo y tamaño de la fuente</div>
</html>
...

3. EXTERNO:
<html>
<head>
<link rel="stylesheet" href="style.css"> /*Solo añadimos en el documento html la ruta del css en el head*/
</head>
</html>

/*Dentro del archivo externo style.css*/
