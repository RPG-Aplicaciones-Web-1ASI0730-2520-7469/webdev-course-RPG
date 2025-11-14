# Fundamentos del Desarrollo Web: HTML y CSS para Principiantes

---

## Resumen del Curso
Este curso tiene una duración aproximada de **1 hora** y busca introducir a estudiantes de secundaria (de 12 a 17 años) al mundo del desarrollo web desde cero. Aprenderás los fundamentos de **HTML** y **CSS**, los dos lenguajes básicos que permiten crear y diseñar páginas web.  
A través de ejemplos visuales y prácticas en **CodePen**, crearás tu primera **página web personal**, entendiendo paso a paso cómo funcionan las páginas que ves todos los días en Internet.

**Duración Total:** ~60 minutos  
**Público Objetivo:** Estudiantes de 12 a 17 años sin experiencia previa en programación  
**Pre-requisitos:** Ninguno  
**Herramientas Necesarias:** Solo tu navegador web y una cuenta gratuita en [CodePen.io](https://codepen.io/)

**Repositorio de Código Fuente:** [Link aquí](https://github.com/RPG-Aplicaciones-Web-1ASI0730-2520-7469/webdev-course-RPG)

---

## Secuencia de Lecciones

---

### Lección 1: ¿Qué es el Desarrollo Web? ( 5 minutos )
- **Descripción:** Descubre cómo se crean las páginas web que visitas todos los días. En esta lección conocerás la diferencia entre **HTML, CSS y JavaScript**, y entenderás qué hace cada uno. Exploraremos cómo los sitios web combinan contenido, estilo e interactividad.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/OOtPqxxqQPg)
- **Conclusiones:** Ahora comprendes que el desarrollo web es el arte de construir y diseñar sitios para Internet. HTML estructura el contenido, CSS le da estilo y JavaScript agrega movimiento e interacción.
- **Empieza a Programar:** [¡Abre CodePen y crea tu primer “Pen”!]([https://codepen.io/pen])
---
En esta lección, aprendimos que el Desarrollo Web es el proceso de construir y diseñar sitios para Internet. Conocimos a los tres lenguajes fundamentales que trabajan juntos para crear lo que vemos en el navegador:

HTML (HyperText Markup Language): Es el esqueleto 🦴. Se encarga de la estructura y el contenido (texto, títulos, imágenes).

CSS (Cascading Style Sheets): Es la ropa y el estilo 🎨. Se encarga de darle apariencia (colores, fuentes y diseño).

JavaScript (JS): Es el cerebro 🧠. Se encarga de la interactividad y el movimiento (botones, animaciones, lógica).

Conclusión clave: Un sitio web combina Contenido (HTML), Estilo (CSS) e Interactividad (JS).
---

### Lección 2: Estructura Básica de una Página Web ( 7 minutos )
- **Descripción:** En esta lección aprenderás qué es **HTML (HyperText Markup Language)** y cómo se organiza una página web usando etiquetas. Construiremos la estructura básica con `<html>`, `<head>` y `<body>`, y añadiremos nuestro primer texto, título y párrafo.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/wRqivyK2tH8)
- **Conclusiones:** Has aprendido cómo se compone una página web y para qué sirve cada parte del HTML. Ahora puedes crear tu primer documento con títulos y párrafos.
- **Práctica:**  
  Crea en CodePen una página con tu nombre como título y una breve descripción personal.

---
1. Estructura Fundamental
Aprendimos que toda página HTML sigue una jerarquía básica, compuesta por el head (información no visible) y el body (contenido visible).
<html> Contenedor principal.
<head> Contiene metadatos, como el título de la pestaña (<title>).
<body> Contiene todo lo que el usuario ve.
<h1>	Título principal de la página.
<p>	Párrafo simple de texto.
  
2. Etiquetas de Contenido
Practicamos cómo usar etiquetas esenciales dentro del <body> para darle significado a nuestro texto.
Etiqueta	Función
<h1>	Título principal de la página.
<p>	Párrafo simple de texto.

3. Código de Práctica
El ejercicio de la lección nos pidió crear una página con nuestro nombre como título y una breve descripción. El código HTML resultante (lo que iría dentro del <body> en CodePen) es el siguiente:
<body>
    <h1>Abraaam</h1>
    <p>¡Hola! Estoy dando mis primeros pasos en el desarrollo web. Con HTML, aprendí a estructurar mi primera página con títulos y párrafos.</p>
    </body>
  
### Lección 3: Etiquetas Comunes en HTML ( 7 minutos )
- **Descripción:** Aprenderás las etiquetas más usadas en HTML: encabezados (`<h1>` a `<h6>`), párrafos (`<p>`), listas (`<ul>` y `<ol>`), enlaces (`<a>`) e imágenes (`<img>`). Verás cómo combinarlas para crear contenido atractivo.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora sabes cómo agregar texto, listas, imágenes y enlaces a tu página. Estas etiquetas son la base de cualquier sitio web.
- **Práctica:**  
  Agrega una lista con tus pasatiempos y un enlace a tu red social favorita (sin revelar información personal).

---

### Lección 4: Introducción al CSS: Colores y Estilos ( 6 minutos )
- **Descripción:** En esta lección conocerás **CSS (Cascading Style Sheets)**, el lenguaje que da color y diseño a las páginas. Aprenderás a cambiar el color del texto, el fondo y el tipo de letra.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/gIyneYwcucM)
- **Conclusiones:** Has aprendido a usar CSS para mejorar la apariencia de tu página. Ahora puedes combinar HTML y CSS para expresar tu propio estilo.

---

### Bloque de Código: HTML 

```html
<h1>¡Hola, CSS!</h1>
<p>Estoy aprendiendo a usar estilos en mi pagina web</p>
```

### Bloque de Código: CSS

```css

h1 {
  color: #299DFC;
  background-color: lightgray;
  text-align: center;
}
body{
  background-color: lightyellow;
}
p{
  color: darkgreen;
  font-family: arial, sans-serif;
}
```

- **Práctica:**  
  Usa CSS en CodePen para cambiar el color del fondo y del texto de tu página.

---

### Lección 5: Selectores y Propiedades en CSS ( 8 minutos)
- **Descripción:** Aprenderás a aplicar estilos usando **selectores** (por etiqueta, clase o id) y a combinar propiedades como `color`, `font-size`, `margin` y `padding`. Descubrirás cómo controlar el diseño de cada parte de tu página.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/BZ7POI6G8Ls)
- **Conclusiones:** Ahora entiendes cómo aplicar estilos específicos a diferentes elementos. Los selectores son la clave para personalizar cada parte de tu sitio.

---

### Bloque de Código: HTML 

```html
<h1 id="titulo-principal">Bienvenido a mi página 🎨</h1>

<p>Este es un párrafo normal, sin estilos especiales.</p>

<p class="importante">
  Este texto es importante y tiene una clase aplicada.
</p>

<p>Otro párrafo común para ver la diferencia.</p>

<div class="caja">
  <h2>Contenido dentro de la caja 📦</h2>
  <p>Esta caja tiene fondo, borde y márgenes. ¡Y se ve genial!</p>
</div>

<footer>
  <p>© 2025 Mi Página Web, Creado por [Tu nombre]</p>
</footer>
```
### Bloque de Código: CSS
```css
p{
  color: blue;
}

.importante {
  color: red;
  background-color: #ffe5e5;
}

#titulo-principal{
  color: #6a0dad;
  text-align: center;
}

.caja {
  background-color: #b3e5fc;
  border: 3px solid #0277bd;
  margin: 25px auto;
  padding: 20px;
  width: 280px;
  border_radius: 12px;
  text-align: center;
}
```
- **Práctica:**  
  Crea una clase llamada `.caja` y aplícale color de fondo, borde y márgenes.

---

### Lección 6: Imágenes, Enlaces y Multimedia ( 7 minutos )
- **Descripción:** Aprenderás cómo insertar imágenes desde Internet, agregar videos de YouTube y enlaces a otras páginas. Verás cómo hacer que tu web sea más visual y dinámica.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/P2zh2uR5pqY)
- **Conclusiones:** Ya puedes combinar texto, imágenes y videos para crear contenido visual. Tu página comienza a cobrar vida.

### Bloque de Código: HTML

```html
<h1> Lección 6</h1>

<!-- Imagen -->
<img src ="https://i.postimg.cc/RZM9PZm6/Fondo.jpg" alt = "Imagen de ejemplo ">

<!-- Enlace -->

<p> Pagina web: </p>

<a href="https://developer.mozilla.org/es/docs/Web/HTML" target = "_blank">PaginaEjemplo</a>

<!-- Video -->
<h2> Video Ejemplo: </h2>
<iframe width="560" height="315" src="https://www.youtube.com/embed/N_qZKPGCxBg?si=2xEXVaq7NOOxeXdo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```

### Bloque de Código: CSS
```css
img {
  width: 300px;
  border-radius: 10px;
  margin-bottom: 10px;
}

iframe {
  width: 90%;
  max-width: 560px;
  border-radius: 10px;
}
```

- **Práctica:**  
  Agrega una imagen representativa y un video embebido de YouTube que te inspire.

---

### Lección 7: Diseño con Cajas (Box Model) ( 7 minutos )
- **Descripción:** Descubrirás cómo funciona el **modelo de cajas** de CSS, que define cómo se organizan los elementos en la pantalla. Aprenderás qué son los márgenes, bordes y rellenos (padding), y cómo ajustar el espacio visual entre tus elementos.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Has entendido cómo cada elemento ocupa un espacio propio. El modelo de cajas es fundamental para ordenar tus páginas y lograr diseños limpios.
- **Práctica:**  
  Crea tres secciones con bordes y márgenes diferentes para practicar el modelo de cajas.

---

### Lección 8: Tu Primera Página Web Personal ( 7 minutos )
- **Descripción:** En esta lección aplicarás todo lo aprendido para construir tu primera **página personal completa**, con tu foto, descripción, enlaces, colores y estilos personalizados.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** ¡Felicidades! Has creado tu primera página web. Has combinado HTML y CSS para diseñar un sitio completo que puedes compartir con amigos y familiares.
- **Práctica:**  
  Diseña una página personal con:
    - Tu nombre y una breve biografía
    - Una imagen
    - Enlaces a tus redes o intereses
    - Un esquema de colores personalizado

---

### Lección 9: Buenas Prácticas y Siguientes Pasos ( 6 minutos )
- **Descripción:** En esta última lección aprenderás las buenas prácticas al crear sitios web: usar etiquetas semánticas, mantener tu código limpio y probar tus diseños en distintos dispositivos. También conocerás los próximos pasos: **HTML avanzado, CSS Flexbox y JavaScript.**
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Has completado los fundamentos del desarrollo web. Ya puedes crear páginas básicas, aplicar estilos y comprender cómo se estructura Internet por dentro. ¡Tu camino como desarrollador web recién empieza!
- **Práctica:**  
  Mejora tu página aplicando las recomendaciones vistas.

---

## Recursos Adicionales

- **Código Fuente Completo:** [Github Link aquí](https://github.com)
- **Todas las actividades prácticas:**

| Nro. de Lección | Actividad | Empezar a Programar |
|-----------------|-----------|---------------------|
| 1 | Conoce el Desarrollo Web | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 2 | Estructura de una Página HTML | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 3 | Etiquetas Básicas en HTML | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 4 | Introducción al CSS | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 5 | Selectores y Propiedades | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 6 | Imágenes y Videos | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 7 | El Modelo de Cajas | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 8 | Página Web Personal | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |
| 9 | Buenas Prácticas Web | [CodePen \| ¡Clic aquí!](https://codepen.io/pen) |

- **Cuestionario:** [Prueba de Conocimientos]()

---

**¡Gracias por completar el curso!**

## Elaboración
Universidad Peruana de Ciencias Aplicadas (UPC)
Facultad de Ingeniería
Periodo 202520
1ASI0730 - Aplicaciones Web
NRC 7469
**Desarrolado por:** RPG
**Líder:** Vivar Cesar, David Ignacio
**Integrantes del Equipo:**

| Apellidos y Nombres             | Código |
|---------------------------------|---|
| Ever Giusephi, Carlos Lavado    | U202224867 |
| Gerardo Valentín, Palacín Lazo  | U20211c201 |
| Howard Robles, Guillermo Arturo | U202222275 |
| Abraam Bernabe, Acosta Elera    | U202414424 |
| David Ignacio, Vivar Cesar      | U202414424 |
| Mike Dylan, Guillen Giraldo     | U202211881 |


**Fecha de Entrega:** XX/11/2025
