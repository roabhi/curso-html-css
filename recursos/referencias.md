# Referencias HTML

Etiquetas básicas de HTML

| **Etiqueta**          | **Descripción**                                                                                                       |
| --------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `<!DOCTYPE html>`     | Declara el tipo de documento como HTML5, requerido al inicio de cada archivo HTML.                                    |
| `<html>`              | El elemento raíz de una página HTML, que contiene todos los demás elementos.                                          |
| `<head>`              | Contiene metadatos y enlaces (por ejemplo, archivos CSS) y no es visible en la página.                                |
| `<title>`             | Establece el título de la página web, visible en la pestaña del navegador.                                            |
| `<meta>`              | Define metadatos, como la codificación de caracteres (`<meta charset="UTF-8">`).                                      |
| `<body>`              | Contiene todo el contenido visible de la página, como texto, imágenes y enlaces.                                      |
| `<h1>` a `<h6>`       | Etiquetas de encabezado para títulos; `<h1>` es el más grande, y `<h6>` es el más pequeño.                            |
| `<p>`                 | Define un párrafo de texto.                                                                                           |
| `<a href="">`         | Crea un hipervínculo; el atributo `href` especifica la URL del enlace.                                                |
| `<img src="" alt="">` | Inserta una imagen; `src` especifica la URL de la imagen y `alt` proporciona un texto alternativo.                    |
| `<ul>`                | Crea una lista desordenada (con viñetas); se usa con `<li>` para elementos de lista.                                  |
| `<ol>`                | Crea una lista ordenada (numerada); también se usa con `<li>`.                                                        |
| `<li>`                | Elemento de lista dentro de `<ul>` o `<ol>`.                                                                          |
| `<div>`               | Un contenedor para agrupar contenido, usado frecuentemente para diseño y estilo.                                      |
| `<span>`              | Un contenedor en línea para texto o elementos, usado para aplicar estilos específicos a un texto.                     |
| `<form>`              | Define un formulario para entrada de usuario; se usa con `<input>`, `<textarea>`, y `<button>`.                       |
| `<input>`             | Un campo de entrada en un formulario; el atributo `type` especifica el tipo (por ejemplo, `text`, `email`, `submit`). |
| `<label>`             | Etiqueta para un campo de entrada, mejorando la accesibilidad.                                                        |
| `<button>`            | Agrega un botón; en un formulario, se usa para enviar (con `type="submit"`) o para ejecutar funciones personalizadas. |
| `<table>`             | Crea una tabla; se usa con las etiquetas `<tr>`, `<th>`, y `<td>`.                                                    |
| `<th>`                | Define una celda de encabezado en una tabla.                                                                          |
| `<td>`                | Define una celda estándar en una tabla.                                                                               |
| `<nav>`               | Define una sección de navegación, generalmente para enlaces a otras páginas o secciones.                              |
| `<main>`              | Define el contenido principal de una página, limitado a una única instancia en cada documento HTML.                   |
| `<footer>`            | Define el pie de página de una sección o página, a menudo para información de derechos de autor o contacto.           |
| `<header>`            | Define el encabezado de una página o sección, frecuentemente contiene logotipos o enlaces de navegación.              |
| `<section>`           | Define una sección en un documento, agrupando contenido relacionado.                                                  |
| `<article>`           | Define un artículo independiente y autosuficiente dentro de una página.                                               |
| `<aside>`             | Define contenido relacionado de manera ligera con el contenido principal, como barras laterales o anuncios.           |

# Referencias CSS

Selectores CSS básicos

| **Selector**          | **Descripción**                                                                                                  |
| --------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `*`                   | Selector universal que selecciona todos los elementos.                                                           |
| `elemento`            | Selecciona todos los elementos de un tipo específico, como `p` para todos los párrafos.                          |
| `.clase`              | Selecciona todos los elementos con una clase específica.                                                         |
| `#id`                 | Selecciona el elemento con un identificador específico.                                                          |
| `elemento, elemento`  | Selecciona múltiples elementos, separados por comas.                                                             |
| `elemento elemento`   | Selecciona todos los elementos hijos dentro de un elemento padre específico (selector descendiente).             |
| `elemento > elemento` | Selecciona todos los elementos hijos directos de un elemento específico.                                         |
| `elemento + elemento` | Selecciona el primer elemento que sigue inmediatamente después de otro elemento específico (selector adyacente). |
| `elemento ~ elemento` | Selecciona todos los elementos que son hermanos de un elemento específico.                                       |
| `[atributo]`          | Selecciona los elementos que contienen un atributo específico, como `[type="text"]`.                             |

## Pseudo selectores CSS básicos

| **Selector**     | **Descripción**                                                                        |
| ---------------- | -------------------------------------------------------------------------------------- |
| `:hover`         | Selecciona un elemento cuando el cursor está sobre él.                                 |
| `:nth-child(n)`  | Selecciona el enésimo elemento hijo de su tipo dentro de un elemento padre.            |
| `::before`       | Inserta contenido antes del contenido de un elemento (se usa con `content` en CSS).    |
| `::after`        | Inserta contenido después del contenido de un elemento (también se usa con `content`). |
| `:first-child`   | Selecciona el primer hijo de un elemento padre.                                        |
| `:last-child`    | Selecciona el último hijo de un elemento padre.                                        |
| `:not(selector)` | Selecciona todos los elementos que no coinciden con el selector dado.                  |
