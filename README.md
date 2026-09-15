# 📘 Trabajo 1 — Fundamentos de HTML

> **Manual de uso, estructura y documentación del proyecto**
>
> Este repositorio contiene **13 ejercicios desarrollados en HTML5** a partir de diferentes imágenes de referencia. El objetivo es practicar la estructura básica de una página web y el uso progresivo de títulos, párrafos, listas, enlaces, imágenes, tablas, formularios, audio y video.

---

## 👤 Autor

**Kevinn Cuervo**

---

## 📌 Descripción del proyecto

El proyecto está compuesto por archivos numerados desde `1.html` hasta `13.html`.  
Cada ejercicio representa una página independiente y trabaja uno o varios conceptos fundamentales de HTML.

El desarrollo se realizó principalmente con **HTML5**, sin depender de frameworks ni librerías externas. Los archivos pueden abrirse directamente en un navegador web.

### Tecnologías y herramientas utilizadas

| Tecnología / herramienta | Uso |
|---|---|
| **HTML5** | Estructura y contenido de las páginas |
| **Visual Studio Code** | Edición del código |
| **Google Chrome / navegador web** | Visualización y prueba de los ejercicios |
| **Git** | Control de versiones |
| **GitHub** | Repositorio remoto principal |
| **GitLab** | Segundo repositorio remoto |
| **PowerShell / Terminal de VS Code** | Ejecución de comandos Git |

---

# 📂 Estructura del proyecto

La estructura general utilizada es:

```text
Trabajo 1/
│
├── 1.html
├── 2.html
├── 3.html
├── 4.html
├── 5.html
├── 6.html
├── 7.html
├── 8.html
├── 9.html
├── 10.html
├── 11.html
├── 12.html
├── 13.html
│
├── Imagenes/
│   ├── Cocina.jpg
│   ├── concierto.jfif
│   └── personas concierto.jpg
│
├── Audios/
│   └── Estadio futbol.mp3
│
└── Videos/
    └── pueblo2.mp4
```

> **Importante:** los nombres de las carpetas y archivos deben coincidir exactamente con las rutas escritas dentro de los documentos HTML.

---

# 🧱 Estructura básica utilizada en los documentos

Todos los ejercicios parten de la estructura básica de HTML5:

```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Kevinn Cuervo">
    <meta name="description" content="Descripción de la página">
    <title>Título de la página</title>
</head>

<body>
    <!-- Contenido visible de la página -->
</body>

</html>
```

### ¿Qué representa cada parte?

| Elemento | Función |
|---|---|
| `<!DOCTYPE html>` | Indica al navegador que el documento utiliza HTML5. |
| `<html lang="es">` | Elemento raíz del documento e indica que el idioma principal es español. |
| `<head>` | Contiene información de configuración y metadatos. |
| `<meta charset="UTF-8">` | Permite mostrar correctamente tildes, ñ y caracteres especiales. |
| `<meta name="author">` | Indica el autor del documento. |
| `<meta name="description">` | Describe brevemente el contenido de la página. |
| `<title>` | Define el texto que aparece en la pestaña del navegador. |
| `<body>` | Contiene todo el contenido visible de la página. |

---

# 📝 Trabajo realizado en cada ejercicio

## 1.html — Plato de la semana

Se desarrolló una página de receta para **Berenjenas fritas**.

Se utilizaron:

- Títulos principales y secundarios.
- Párrafos.
- Saltos de línea.
- Organización textual de ingredientes y preparación.

Etiquetas principales:

```html
<h1>
<h2>
<p>
<br>
```

---

## 2.html — Página inicial de Juan Tuesta

Se creó una página personal con una breve presentación y una lista numerada de enlaces favoritos.

Conceptos trabajados:

- Encabezados.
- Párrafos.
- Listas ordenadas.
- Texto en cursiva.

Etiquetas principales:

```html
<h1>
<h2>
<p>
<ol>
<li>
<i>
```

---

## 3.html — Listas anidadas

Se amplió la página anterior agregando una lista secundaria con nombres dentro de la opción **Páginas personales**.

Conceptos trabajados:

- Listas ordenadas.
- Listas con viñetas.
- Listas anidadas.

Etiquetas principales:

```html
<ol>
<ul>
<li>
```

> Para una estructura HTML semánticamente correcta, la lista secundaria `<ul>` debe ubicarse dentro del `<li>` al que pertenece.

Ejemplo recomendado:

```html
<ol>
    <li>
        Páginas personales
        <ul>
            <li>Charles F. Goldfarb</li>
            <li>Lou Burnard</li>
            <li>Tim Berners-Lee</li>
        </ul>
    </li>
</ol>
```

---

## 4.html — Noticiero Next University

Se desarrolló una página informativa sobre programas de tecnología y negocios.

Conceptos trabajados:

- Jerarquía de encabezados.
- Párrafos extensos.
- Texto en negrita.
- Texto en cursiva.

Etiquetas principales:

```html
<h1>
<h2>
<h3>
<p>
<b>
<i>
```

---

## 5.html — Destinos turísticos

Se creó una lista de países de América y una lista secundaria de ciudades para cada país.

Conceptos trabajados:

- Listas numeradas.
- Listas anidadas.
- Negrita para países.
- Cursiva para ciudades.

Ejemplo de estructura recomendada:

```html
<ol>
    <li>
        <b>Colombia</b>
        <ol>
            <li><i>Bogotá</i></li>
            <li><i>Cartagena de Indias</i></li>
        </ol>
    </li>
</ol>
```

---

## 6.html — Enlaces externos

Se trabajó con hipervínculos hacia sitios externos.

Los enlaces permiten visitar:

- Google.
- Aldea Global.
- Manual de HTML.

Ejemplo:

```html
<a href="https://www.google.com/">Google</a>
```

La etiqueta `<a>` crea el enlace y el atributo `href` establece su destino.

---

## 7.html — Secciones y líneas divisorias

Se construyó una página más extensa con varias categorías:

- Enlaces favoritos.
- Páginas personales.
- Páginas de referencia.
- Portales.
- Publicaciones.

También se utilizó:

```html
<hr>
```

para crear líneas horizontales entre las secciones.

El archivo contiene además un enlace local:

```html
<a href="3.html">Páginas personales</a>
```

Este tipo de enlace permite navegar hacia otro archivo HTML del mismo proyecto.

---

## 8.html — Página de concierto e imágenes

Se creó una página relacionada con conciertos utilizando imágenes locales.

Se trabajó con:

```html
<img>
<table>
<tr>
<th>
```

Ejemplo de ruta relativa:

```html
<img src="Imagenes/personas concierto.jpg"
     alt="Concierto"
     width="70">
```

> Las rutas relativas son necesarias para que las imágenes funcionen tanto en el computador local como después de subir el proyecto a GitHub o GitLab.

No se recomienda utilizar rutas absolutas de Windows como:

```text
C:\Users\...\Imagenes\archivo.jpg
```

Debe utilizarse una ruta relativa como:

```html
<img src="Imagenes/concierto.jfif" alt="Concierto">
```

---

## 9.html — Cartelera de vuelos

Se construyeron tablas para representar:

- Llegadas.
- Salidas.
- Aerolínea.
- Número de vuelo.
- Estado.
- Hora estimada.
- Puerta.

Etiquetas principales:

```html
<table>
<tr>
<th>
<td>
```

Ejemplo:

```html
<table border="1">
    <tr>
        <th>Aerolínea</th>
        <th>Nro. vuelo</th>
    </tr>
    <tr>
        <td>AIRLAN</td>
        <td>355</td>
    </tr>
</table>
```

---

## 10.html — Recetas.com

Se desarrolló una página de gastronomía con:

- Imagen de encabezado.
- Enlaces externos.
- Lista de ingredientes.
- Lista numerada de preparación.
- Texto en negrita.
- Encabezados de diferentes niveles.

Se combinaron listas ordenadas y no ordenadas:

```html
<ul>
    <li>Ingrediente</li>
</ul>

<ol>
    <li>Paso de preparación</li>
</ol>
```

---

## 11.html — Formulario de registro

Se desarrolló un formulario que permite ingresar diferentes tipos de información.

Campos incluidos:

- Nombre de usuario.
- Correo electrónico.
- Edad.
- Género.
- Medio por el que conoció la tienda.
- Comentarios.
- Aceptación de términos.
- Botón de registro.

Etiquetas utilizadas:

```html
<form>
<label>
<input>
<select>
<option>
<textarea>
```

Ejemplos de tipos de `input` utilizados:

```html
<input type="text">
<input type="email">
<input type="number">
<input type="radio">
<input type="submit">
```

Para la aceptación de términos se recomienda usar:

```html
<input type="checkbox">
```

porque permite representar una casilla de aceptación.

---

## 12.html — Reproductor de audio

Se agregó un reproductor de audio mediante HTML5.

```html
<audio controls>
    <source src="Audios/Estadio futbol.mp3"
            type="audio/mpeg">
    Tu navegador no soporta el elemento de audio.
</audio>
```

El atributo `controls` hace visibles los botones de:

- Reproducir.
- Pausar.
- Volumen.
- Barra de progreso.

La etiqueta `<source>` indica la ubicación del archivo y su formato.

---

## 13.html — Reproductor de video

Se agregó un video mediante HTML5.

```html
<video controls width="420" height="240">
    <source src="Videos/pueblo2.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
</video>
```

Se utilizan los atributos:

- `controls`
- `width`
- `height`

y un archivo multimedia mediante `<source>`.

---

# 🏷️ Etiquetas HTML utilizadas

| Etiqueta | Función |
|---|---|
| `<!DOCTYPE html>` | Declara que el documento utiliza HTML5. |
| `<html>` | Contiene todo el documento HTML. |
| `<head>` | Contiene metadatos y configuración. |
| `<meta>` | Define información como codificación, autor y descripción. |
| `<title>` | Define el título de la pestaña del navegador. |
| `<body>` | Contiene el contenido visible. |
| `<header>` | Representa el encabezado de una página o sección. |
| `<main>` | Contiene el contenido principal. |
| `<footer>` | Define el pie de página. |
| `<h1>` | Título principal. |
| `<h2>` | Título secundario. |
| `<h3>` | Subtítulo de tercer nivel. |
| `<p>` | Define un párrafo. |
| `<br>` | Inserta un salto de línea. |
| `<hr>` | Inserta una línea horizontal temática. |
| `<b>` | Muestra texto en negrita. |
| `<i>` | Muestra texto en cursiva. |
| `<ol>` | Crea una lista ordenada o numerada. |
| `<ul>` | Crea una lista con viñetas. |
| `<li>` | Representa un elemento de una lista. |
| `<a>` | Crea un hipervínculo. |
| `<img>` | Inserta una imagen. |
| `<table>` | Crea una tabla. |
| `<tr>` | Define una fila de tabla. |
| `<th>` | Define una celda de encabezado. |
| `<td>` | Define una celda de datos. |
| `<form>` | Agrupa los controles de un formulario. |
| `<label>` | Define la descripción de un campo. |
| `<input>` | Crea diferentes controles de entrada. |
| `<select>` | Crea una lista desplegable. |
| `<option>` | Define una opción de una lista desplegable. |
| `<textarea>` | Crea un campo de texto de varias líneas. |
| `<audio>` | Inserta un reproductor de audio. |
| `<video>` | Inserta un reproductor de video. |
| `<source>` | Define el archivo multimedia utilizado por audio o video. |

---

# ⚙️ Atributos utilizados

| Atributo | Uso |
|---|---|
| `lang="es"` | Indica que el documento está escrito principalmente en español. |
| `charset="UTF-8"` | Configura la codificación de caracteres. |
| `name` | Define el nombre de un metadato o campo de formulario. |
| `content` | Establece el contenido de un metadato. |
| `href` | Define el destino de un enlace. |
| `src` | Indica la ubicación de una imagen, audio o video. |
| `alt` | Proporciona un texto alternativo para una imagen. |
| `width` | Establece el ancho de una imagen o video. |
| `height` | Establece la altura de un video. |
| `border` | Define el borde de una tabla en los ejercicios realizados. |
| `cellpadding` | Define espacio interior en las celdas de una tabla. |
| `cellspacing` | Define separación entre celdas. |
| `id` | Identifica de manera única un elemento. |
| `for` | Relaciona un `<label>` con un campo mediante su `id`. |
| `type` | Define el tipo de un `<input>` o de un archivo multimedia. |
| `placeholder` | Muestra un texto de ejemplo dentro de un campo. |
| `value` | Define el valor asociado a un control. |
| `controls` | Muestra los controles del reproductor de audio o video. |

> `border`, `cellpadding` y `cellspacing` funcionan en este ejercicio, aunque en proyectos modernos normalmente su apariencia se controla mediante CSS.

---

# 🖼️ Rutas relativas y archivos multimedia

Una ruta relativa busca el archivo tomando como referencia la ubicación del HTML.

Ejemplo:

```html
<img src="Imagenes/Cocina.jpg">
```

significa:

```text
Trabajo 1/
├── 10.html
└── Imagenes/
    └── Cocina.jpg
```

Lo mismo aplica para audio:

```html
<source src="Audios/Estadio futbol.mp3">
```

y video:

```html
<source src="Videos/pueblo2.mp4">
```

## ¿Por qué no usar rutas absolutas?

Una ruta como:

```text
C:\Users\Kevinn Cuervo\Documents\...
```

solamente funciona en ese computador.

Cuando el proyecto se sube a GitHub o GitLab, esa ubicación no existe. Por eso todos los recursos del proyecto deben utilizar **rutas relativas**.

---

# ▶️ Cómo ejecutar el proyecto

No se necesita instalar ninguna dependencia.

1. Descargar o clonar el repositorio.
2. Abrir la carpeta `Trabajo 1` en Visual Studio Code.
3. Seleccionar cualquiera de los archivos `1.html` a `13.html`.
4. Guardar los cambios con `Ctrl + S`.
5. Abrir el archivo HTML directamente en el navegador o mediante una extensión como Live Server.
6. Verificar que las carpetas `Imagenes`, `Audios` y `Videos` estén dentro del proyecto.

---

# 🔀 Control de versiones con Git

El proyecto utiliza Git para guardar el historial de cambios.

## Comandos principales

### Consultar el estado

```bash
git status
```

Muestra archivos nuevos, modificados o eliminados.

### Preparar cambios

```bash
git add .
```

Agrega todos los cambios al área de preparación.

También puede utilizarse:

```bash
git add -A
```

para incluir archivos nuevos, modificados y eliminados.

### Crear un commit

```bash
git commit -m "Descripción de los cambios"
```

Ejemplo:

```bash
git commit -m "Corrijo ejercicios HTML y archivos multimedia"
```

### Publicar cambios

```bash
git push
```

---

# ☁️ Configuración de GitHub y GitLab

Este proyecto fue configurado para utilizar **GitHub como repositorio principal de consulta (`fetch`)** y enviar los mismos commits tanto a **GitHub como a GitLab** mediante un solo `git push`.

## Repositorios utilizados

**GitHub**

```text
https://github.com/kevinncuervo/Trabajo-1.git
```

**GitLab**

```text
https://gitlab.com/kevinncuervo-group/trabajo-1.git
```

---

## Configuración del remoto

Primero se configura GitHub como URL principal:

```bash
git remote set-url origin https://github.com/kevinncuervo/Trabajo-1.git
```

Si existían configuraciones anteriores de envío, pueden limpiarse con:

```bash
git config --unset-all remote.origin.pushurl
```

Luego se agregan los dos destinos de `push`.

### GitHub

```bash
git remote set-url --add --push origin https://github.com/kevinncuervo/Trabajo-1.git
```

### GitLab

```bash
git remote set-url --add --push origin https://gitlab.com/kevinncuervo-group/trabajo-1.git
```

Para comprobar la configuración:

```bash
git remote -v
```

El resultado esperado es similar a:

```text
origin  https://github.com/kevinncuervo/Trabajo-1.git (fetch)
origin  https://github.com/kevinncuervo/Trabajo-1.git (push)
origin  https://gitlab.com/kevinncuervo-group/trabajo-1.git (push)
```

De esta forma:

```text
                         ┌────────────► GitHub
Proyecto local ─ git push
                         └────────────► GitLab
```

---

# 🔄 Flujo normal de trabajo

Después de modificar cualquier archivo:

```bash
git status
git add .
git commit -m "Descripción de los cambios"
git push
```

Ejemplo:

```bash
git add .
git commit -m "Actualizo ejercicios 12 y 13"
git push
```

Con la configuración utilizada en este proyecto, el último comando envía el commit a los dos repositorios remotos.

---

# 🧩 Solución de problemas frecuentes

## El audio aparece en `0:00 / 0:00`

Normalmente significa que el navegador no encuentra el archivo.

Se debe comprobar:

- Nombre de la carpeta.
- Nombre del archivo.
- Extensión.
- Mayúsculas y minúsculas.
- Ruta relativa.

Ejemplo correcto:

```html
<source src="Audios/Estadio futbol.mp3"
        type="audio/mpeg">
```

---

## Una imagen funciona en el PC pero no en GitHub

Probablemente está utilizando una ruta absoluta.

Incorrecto:

```text
C:\Users\Kevinn Cuervo\Documents\...\imagen.jpg
```

Correcto:

```html
<img src="Imagenes/imagen.jpg">
```

---

## GitHub rechaza un video por tamaño

GitHub rechaza archivos individuales demasiado grandes para un repositorio Git normal. En este proyecto ocurrió al intentar incluir un video de aproximadamente 150 MB.

La solución aplicada es utilizar un video más pequeño.

Si el archivo grande ya quedó guardado en un commit local que todavía no ha sido publicado, eliminarlo de la carpeta no siempre es suficiente, porque Git conserva el archivo dentro del historial del commit.

En ese caso se debe revisar cuidadosamente el historial antes de volver a publicar.

---

## `Repository not found`

Se debe comprobar que el nombre de usuario y la URL del repositorio sean exactamente correctos.

En este proyecto el usuario correcto es:

```text
kevinncuervo
```

y no una variante con una sola `n`.

---

# 📋 Buenas prácticas aplicadas

- Uso de `<!DOCTYPE html>`.
- Idioma declarado con `lang="es"`.
- Codificación `UTF-8`.
- Metadatos de autor y descripción.
- Indentación del código.
- Organización de recursos en carpetas.
- Uso de rutas relativas para multimedia.
- Uso de Git para control de versiones.
- Publicación del mismo proyecto en GitHub y GitLab.
- Mensajes de commit descriptivos.
- Separación de los ejercicios por archivos numerados.

---

# 🚀 Mejoras futuras

El proyecto puede seguir evolucionando incorporando:

- CSS para mejorar el diseño visual.
- Diseño adaptable a dispositivos móviles.
- Etiquetas semánticas como `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>` en más ejercicios.
- Validación adicional de formularios.
- Enlaces internos mediante `id`.
- Accesibilidad mejorada.
- Nombres de archivos multimedia sin espacios.
- Uso de `<strong>` y `<em>` cuando se quiera aportar significado semántico además del formato visual.

---

# ✅ Conclusión

Este trabajo permite practicar de forma progresiva los principales elementos de HTML: estructura básica, encabezados, texto, listas, enlaces, imágenes, tablas, formularios y contenido multimedia.

Además del desarrollo de las páginas, el proyecto incorpora control de versiones con Git y publicación en **GitHub y GitLab**, permitiendo conservar el historial de cambios y mantener una copia del proyecto en ambas plataformas.

---

## 📎 Repositorios

- **GitHub:** `https://github.com/kevinncuervo/Trabajo-1`
- **GitLab:** `https://gitlab.com/kevinncuervo-group/trabajo-1`

---

**Autor:** Kevinn Cuervo  
**Proyecto:** Trabajo 1 — HTML
