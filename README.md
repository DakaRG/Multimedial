# Multimedial
##Taller Multimedia
#### Cultura web y arte digital

Ejercicio 1, semana 1

```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Archivo</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: ambar;
  /* Define que el fondo de toda la página sea ámbar */

  color: bronce;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

Semana 2: Enlaces (links)

```
//código entregado por el profe//
<a href="pagina2.html">Ir a la página 2</a>
```
##Cómo lo apliqué a mi código: 

```
<a href="obras.html">Obras</a>
<a href="obrasGrabado.html">Grabados</a>
<a href="contacto.html">Contáctame!</a>
<a href="index.html">Inicio</a>

```
de este modo los links llevan a las 4 iferentes páginas hasta el momento creadas

```
<a href="https://www.instagram.com/retratos.animalitos_rg?igsh=aGRlZTJ4eGd0OGhs
" target="_blank">IG de retratos</a> <br>

<a href="https://www.instagram.com/daka.rg?igsh=MTI5ZzYxdHNrbWU1Yw==" target="_blank">IG fanart</a>
```
Se encuentra en la sección contactos, llevando en una pestaña nueva donde se abren mis cuentas de Instagram.

#BONUS
Hacer la imagen clickeable (como link)
<a href="obra.html">
  <img src="inicio.jpg" alt="Ir a obra" width="300">
</a>
Esto transforma la imagen en un botón visual.
//Hasta la fecha 02.04.2026 hice un uso de este bonus que luego fue quitado, planeo usarlo mas adelante.//




#MI INDEX 
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Casita Multimedial Daka</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Comic, sans-serif;
            background-color: #d4a027;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(237, 193, 122);
            margin: 20px 0;
            padding: 40px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: 50%;
        }

        /* Encabezado */
        .bloque h1 {
            font-size: 3.4rem;
            margin-top: 10px;
            color:black
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }    

        .enlaces {
            text-align: right;           /* Los pone a la derecha */
            max-width: 700px;
            margin: 50px auto 0 auto;    /* Distancia arriba y centrado */
            font-size: 1.5rem;
            padding: 0 20px;    
        }

        .enlaces img {
            width: 80px;
            height: auto;
            display: block;
            margin-bottom: 8px;
        }

    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <h1>Casita Multimedial</h1>
            <img src="img/Fullmontaje2.jpg" alt="Montaje final Intersecciones" max width="100">
            
            <p>
                Daniela Reyes Guerrero <br>
                Estudiante en cuarto año de Artes Visuales <br>
                Universidad Finis Terrae <br>
                Mención en grabado

                <br><br>

                Mi trabajo consta de una exploración en base a diferentes aspectos de lo cotidiano, en busca de honrar mis experiencias y vivencias dentro el espacio íntimo y familiar.
            </p>
        </div>

    </div>

<br>

 
<!--<a href="obras.html">
  <img src="img/tacita.jpg" alt="Ir a obras" width="100"><br>

<a href="contacto.html">Contactame!</a>

<a href="obrasGrabado.html">Grabados</a> -->

<div class="enlaces">
        <a href="obras.html">Obras</a>
           <!-- <img src="img/tacita.jpg" alt="Ir a obras"><br>
            Obras
        </a> -->
        <a href="obrasGrabado.html">Grabados</a>
        <a href="contacto.html">Contáctame!</a>
    </div>


</body>
</html>
```

#MI PRIMERA PÁGINA "OBRAS"
```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Obras</title>
    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Comic, sans-serif;
            background-color: #b5853d;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 60%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(239, 241, 200);
            margin: 20px 0;
            padding: 50px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
        .enlaces {
            text-align: right;           /* Los pone a la derecha */
            max-width: 700px;
            margin: 50px auto 0 auto;    /* Distancia arriba y centrado */
            font-size: 1.5rem;
            padding: 0 20px;    
        }

        .enlaces img {
            width: 80px;
            height: auto;
            display: block;
            margin-bottom: 8px;
        }
    </style>

</head>

<body>
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/nalasonrisa.jpg" alt="dibujodeNalaSonriendo" width="300" height="500"> 
            <h2>NaliCaras</h2>
            <p>
                Este trabajo es parte de una serie de dibujos de lapices pastel sobre papel kraft,
                donde retrato diferentes expresiones de mi mascota Nala (160x210cm)
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/nalasentada.jpg" alt="DibujoNalaSentada">
            <h2>Nalicaras pt2</h2>
            <p>
                Otra exploración de las expresiones de Nala (160x210cm)
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/retGordo.jpg" alt="PinturaAcrilicaGordo">
            <h2>Retrato de "Gordo"</h2>
            <p>
                Retrato acrilico sobre rueda de madera 5mm (15cm).
            </p>
        </div>

    </div>

<!-- <h1>Mi Trabajo</h1>

<img src="img/nalasonrisa.jpg" alt="nalasonrisa" width="300" height="500">

<p>Mi trabajo se caracteriza por una investigación y retrato de lo cotidiano, lo íntimo del hogar</p>
-->
<div class="enlaces">
    <a href="index.html">Inicio</a><br>
    <a href="contacto.html">Contáctame!</a> 
    <a href="obrasGrabado.html">Grabados</a>
<div>

</body>
</html>

```

#PAGINA 3: Obras Grabado
```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>ObrasGrabado</title>
    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Comic, sans-serif;
            background-color: #b5853d;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 60%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(239, 241, 200);
            margin: 20px 0;
            padding: 50px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
        .enlaces {
            text-align: right;           /* Los pone a la derecha */
            max-width: 700px;
            margin: 50px auto 0 auto;    /* Distancia arriba y centrado */
            font-size: 1.5rem;
            padding: 0 20px;    
        }

        .enlaces img {
            width: 80px;
            height: auto;
            display: block;
            margin-bottom: 8px;
        }
    </style>

</head>

<body>
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/Mermelada.jpg" alt="grabadomermelada" width="300" height="500"> 
            <h2>Cero Ausencia</h2>
            <p>
                Este trabajo es parte de una serie de grabados para mi proyecto de grado, donde
                reinterpreto los textos dentro de los empaques de consumo diario
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/Cafe.jpg" alt="grabadodecafe">
            <h2>NesTradición</h2>
            <p>
                exploracion proyecto de grado
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/CajaLeche.jpg" alt="grabadocajadeleche">
            <h2>Casita & Co</h2>
            <p>
                exploración proyecto de grado 
            </p>
        </div>

    </div>

<!-- <h1>Mi Trabajo</h1>

<img src="img/nalasonrisa.jpg" alt="nalasonrisa" width="300" height="500">

<p>Mi trabajo se caracteriza por una investigación y retrato de lo cotidiano, lo íntimo del hogar</p>
-->
<div class="enlaces">

    <a href="index.html">Inicio</a><br>
    <a href="obras.html">ir a Obras</a> <br>
    <a href="contacto.html">Contáctame!</a> 
</div>

</body>
</html>
```

Tengo carpetas "fanstasmas" donde aplico cosas pedidas al código, las llamo "Ejemplo____.html". Allí hay códigos con modificaciones aún no visibles en la página pero que me sirven de experimentación y aprendizaje sin perjudicar el original.
