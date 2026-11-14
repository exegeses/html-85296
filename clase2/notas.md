# notas clase II

## Atributos
> Los atributos son modificadores de un elemento

<elemento atributo="valor"> contenido </elemento>  
<elemento atributo="valor" atributo2="valor2"> contenido </elemento>  

## Enlaces o vínculos

<a href="url" target="_blank">contenido</a>


## Imágenes

<img src="ruta">
<img src="ruta" alt="descripción">

> El atributo alt se utiliza para escribir una descripción de la imagen que se utilizará para visitantes de nuestro sitio que tengan alguna discapacidad visual
> Queríamos utilizar alguna descripción breve ya que el usuario que ingrese con las opciones de accesibilidad en su navegador va a oír esta descripción


### Sitios para descargar imágenes

    íconos  
        Flaticon <https://www.flaticon.com/>
        Freepik <https://www.freepik.com/icons>
        SVGRepo <https://www.svgrepo.com/>

    fotografías
        Unsplash <https://unsplash.com/es>
        Pexels  <https://www.pexels.com/es-es/>
        Freepik <https://www.freepik.com/>

### Sitio de generación de imágenes por IA

    Grok  <https://grok.com/>      
    ChatGPT <https://chatgpt.com/>
    Gemini  <https://gemini.google.com/app>
    Leonardo <https://app.leonardo.ai/>  
    Higgsfield <https://higgsfield.ai/>        


## Estructura de un documento html
> Cuando generamos un documento html este debe tener la siguiente estructura:

<!DOCTYPE html>
<html>
    <head>
        Elementos NO visuales (no se ven directamente dentro de la página)
    </head>
    <body>
        Elementos visuales (se ven directamente dentro de la página)
    </body>
</html>

> Todo el contenido que queremos ver dentro de la página debería estar dentro del elemento body

    párrafos    
    imágenes    
    video

## Enunciados o encabezados
Los enunciados se crearon para establecer el tema de una página
desde h1 hasta h6
El h1 es el tema principal y los demás van a ir disminuyendo en importancia
```html
<h1>Tema principal</h1>
<h2>Subtema</h2>
<h3>...</h3>
```

## Elementos de maquetado semántico

Maquetar significa pasar a código HTML y CSS el contenido de nuestro prototipo/diseño

En HTML tenemos ciertos elementos que fueron creados para poder dar estructura a nuestras páginas. Fueron creados para maquetar
Algunos de estos elementos son:
```html
<header>
    <nav>
<main>
    <section>
        <article>
<footer>
```