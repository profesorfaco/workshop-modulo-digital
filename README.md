# Procesos de Producción | Módulo Digital | 2020-2

### Front End | Código fuente desde el diseño

**Partamos recordando una cita**:

> Los objetos digitales aparecen ante los usuarios humanos como seres coloridos y visibles. **Al nivel de la programación son archivos de texto**; en el sistema operativo son códigos binarios; a nivel de las tarjetas de circuitos, son señales generadas por los valores del voltaje y la operación de entradas lógicas (Hui, 2017: 88)

**Agreguemos una analogía**: 

Se ofrece puesto de trabajo en una empresa japonesa. Solo se requiere dominio de inglés. Tu lengua materna es el castellano, y tienes un buen nivel de inglés. 

¿Cómo te iría en ese trabajo si es que, además de inglés, supieras algo de japonés? ¿Mejor, igual o peor? ¿Por qué?

**Mezclemos la cita y la analogía**: 

Los objetos digitales son archivos de texto. Como archivos de texto, se escriben. Ahora, pensemos en el dominio del japonés escrito como el dominio de lenguajes de descripción o programación de objetos digitales. 

No corresponde desalentarnos cuando no podemos escribir este tercer idioma al nivel de un nativo al que se le exige escribirlo, todos los días, de la mejor manera posible. 

**Lo que sí nos correspode es dominar, de forma óptima, nuestra lengua materna y practicar el idioma funcional para los intercambios; si el contexto lo permite, saquemos ventaja con el dominio del tercer idioma**.

<table>
<tr><td>Castellano</td><td>≈</td><td>Diseño</td><td>Principios operativos, perceptuales y simbólicos de la forma</td></tr>
<tr><td>Inglés</td><td>≈</td><td>Desarrollo Ágil</td><td>Idioma funcional para los intercambios en el desarrollo de objetos digitales</td></tr>
<tr><td>Japonés</td><td>≈</td><td>Programación</td><td>Lenguaje de descripción o programación de objetos digitales</td></tr>
</table>

- - - - - - - - - - 

**Para el trabajo grupal final del Módulo Digital, nos basaremos en el trabajo desarrollado para el Módulo Gráfico**. De allí tomaremos:

1. colores
2. textos
3. fuentes
4. imágenes

Con estos elementos (operativos, perceptuales y simbólicos) describiremos y programaremos una página web, tipo [landing page](https://es.wikipedia.org/wiki/P%C3%A1gina_de_aterrizaje), que será la versión digital, interactiva y dinámica del fanzine. 

Para describir y programar esta página aprovecharemos [Bootstrap](https://getbootstrap.com/), lo que nos facilitará el trato con [HTML](https://github.com/profesorfaco/dno075-2020/wiki/HTML) y [CSS](https://github.com/profesorfaco/dno075-2020/wiki/CSS), que son lenguajes descriptivos, y [JavaScript](https://github.com/profesorfaco/dno075-2020/wiki/JavaScript), que es un lenguaje de programación; los tres lenguajes, operando en conjunto, son el código fuente.

Para escribir el código fuente, será necesario tener instalado uno de los siguientes editores:

- [Sublime Text](https://www.sublimetext.com/) 
- [Atom.io](https://atom.io/)
- [Brackets](http://brackets.io/) 

Para las revisiones y publicación final, usaremos [GitHub](https://github.com/). 

**¡Una recomendación! Para abordar lo que sigue, conviene que los grupos auto-organicen el aprendizaje sobre colores, textos, fuentes e imágenes. Que un integrante se encargue de un tema. Luego, si a un grupos de 6 integrantes les resto 4, quedan 2 integrantes que podrán abordar 2 temas más: [HTML](https://github.com/profesorfaco/dno075-2020/wiki/HTML) y [CSS](https://github.com/profesorfaco/dno075-2020/wiki/CSS).**

- - - - - - - - - - - - - - - - 

### 1. colores 

1.1. Cambiar sus colores para impresión (Pantone) por equivalentes para pantalla (HEX/HTML) → https://www.pantone.com/color-finder/

1.2. Revisar el [*contrast ratio*](https://www.w3.org/TR/WCAG21/#contrast-minimum) para asegurar la legibilidad. Ajustar aquellos colores que ofrezca un *contrast ratio* insuficiente para negro (#000000) o blanco (#FFFFFF) puestos en nivel de figura (Foreground) y fondo (Background) → https://webaim.org/resources/contrastchecker/

> A [contrast ratio](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) of 3:1 is the minimum level recommended by ISO-9241-3 and ANSI-HFES-100-1988 for standard text and vision. The 4.5:1 ratio is used in this provision to account for the loss in contrast that results from moderately low visual acuity, congenital or acquired color deficiencies, or the loss of contrast sensitivity that typically accompanies aging.

1.3. Una vez tengan los colores definitivos, podrán aprovechar las variables CSS → [https://developer.mozilla.org/es/docs/Web/CSS/--*](https://developer.mozilla.org/es/docs/Web/CSS/--*)

**Más información en:**

- *¿Cuáles son los códigos de color de HTML?* → https://htmlcolorcodes.com/es/
- *Understanding Web Accessibility Color Contrast Guidelines and Ratios* → https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/

- - - - - - - - - - - - - - - - 
 
### 2. textos

2.1. Revisar la credibilidad del texto original → http://credibility.stanford.edu/guidelines/index.html

2.2. Establecer un tono de voz pertinente al mensaje → https://www.nngroup.com/articles/tone-of-voice-dimensions/

2.3. Editar el textos para su lectura en web → https://www.nngroup.com/articles/how-users-read-on-the-web/

**Más información en:**

- *Concise, SCANNABLE, and Objective: How to Write for the Web* → https://www.nngroup.com/articles/how-users-read-on-the-web/
- *Las 11 reglas de oro para escribir contenido en tu página web* → https://www.jimdo.com/es/blog/escribir-contenido-pagina-web/

- - - - - - - - - - - - - - - - 

### 3. fuentes 

3.1. Buscar las fuentes tipográficas en el catálogo de Google Fonts; en caso de no encontrarla(s), reemplácenla(s) por otra(s) disponible(s) en el mismo catálogo → https://fonts.google.com/

Es importanta considerar que:

> Siempre hay excepciones, siempre hay excusas para las sorpresas y los trucos. Pero tal vez podamos ponernos de acuerdo en que, en general, la tipografía puede realizar los siguientes servicios […] invitar al lector a entrar en el texto; mostrar el tenor y significado del texto; vincular el texto con otros elementos; [e] inducir un estado de enérgico reposo, que es la condición ideal para la lectura (Bringhurst, 2008:31)

3.2. Escoger una escala de cuerpos tipográficos que empice en un tamaño que permita inducir al estado de enérgico reposo en la lectura de los párrafos. Además de un tamaño para **párrafo** (normal), **párrafo destacado** (más grande de lo normal) y notas al margen (más pequeño de lo normal), pueden establecer tamaños para distintos niveles de encabezados (un máximo de 6, con 1 título y 5 subtítulos en distintos tamaños) → https://bootstrapcreative.com/bootstrap-text-sizes/

**Más información**

- *The Elements of Typographic Style Applied to the Web* → http://webtypography.net/
- *Typography Terms Cheat Sheet* → https://www.nngroup.com/articles/typography-terms-ux/

- - - - - - - - - - - - - - - - 

### 4. imágenes

4.1. Crear tres versiones para cada una de las imágenes que utilizaron en el fanzine y quieran utilizar en su versión digital, interactiva y dinámica. Cada una de tales versiones tendrá que responder a *smartphone (small)*, *tablet (medium)* o *desktop (large)*. 

Para crear estas versiones, y debido a la gran [variedad de pantallas con tamaños y resoluciones distintas](http://screensiz.es/), no existen recetas infalibles. Todo es una apuesta. 

Pero podemos quedar en un lugar suficientemente seguro considerando los tamaños de ancho de pantalla que usa [Bootstrap](https://getbootstrap.com/docs/4.5/layout/overview/#responsive-breakpoints) como referencia para sus cambios entre *smartphone (small)*, *tablet (medium)* y *desktop (large)*, que son, respectivamente: 576px, 768px y 992px.

Si ya tenemos un ancho para la imagen, nos falta un alto. En este punto podemos encontrar un lugar más seguro aprovechando [la relación de aspecto](https://es.wikipedia.org/wiki/Relaci%C3%B3n_de_aspecto) más probable; podría ser que una imagen que se vea a pantalla completa en *smartphone (small)* se acerque al formato Panavision (2.39:1). Una imagen que se vea a pantalla completa en *tablet (medium)* podría estar más cerca de la razón 3:2. Y podría ser que una imagen que se ve completa en *desktop (large)* esté más cerca del 16:9.

4.2. Guardar copia de cada imagen (en GIF, JPG o PNG), con atención a los pesos resultantes → https://nbadiola.com/peso-ideal-fotografia-para-web/

**Más información**

- *Optimización de imágenes* → https://helpx.adobe.com/es/photoshop-elements/using/optimizing-images.html
- *Lazy loading de imágenes ya forma parte del estándar HTML* → https://carlosazaustre.es/lazy-loading-image
- *Use el atributo alt* → https://www.w3.org/QA/Tips/altAttribute.html.es

- - - - - - - - - - - - - - - - 

### ENCARGO

**Cada versión digital, interactiva y dinámica de fanzine debe desarrollarse desde una [plantilla](https://github.com/profesorfaco/digital/tree/main/plantilla)** que queda disponible en este repositorio el día lunes 30 de noviembre. **La [plantilla](https://github.com/profesorfaco/digital/tree/main/plantilla) incluye tres páginas y un estilo (que aplica a dos de las páginas), además de imágenes con tamaños de referencia**:
	
- [index.html](https://profesorfaco.github.io/digital/plantilla/index.html) → resultado final (estilo y contenido)
- [surface.html](https://profesorfaco.github.io/digital/plantilla/surface.html) → decisiones de estilo (sin contenido)
- [skeleton.html](https://profesorfaco.github.io/digital/plantilla/skeleton.html) → decisiones de contenido (sin estilo)

Su trabajo grupal será evaluado con el uso de **[una rúbrica](https://docs.google.com/spreadsheets/d/1r9Cf1m2blnWIl97_lX4GKQNjiEJf7nhrdf9uMhQyWVs/edit?usp=sharing), que está disponible en la carpeta del Drive a la que todo el curso tiene acceso**.

- - - - - - - - - - - - - - - 

### FECHA(S) DE ENTREGA DEL ENCARGO

Cuentan con 10 días hábiles. Según la fecha de su entrega, podrán obtener bonificación:

| Día     | Fecha               | Bonificación |
|:--------:|:-------------------|:------------:|
|  0      | Lunes 30/11         |    + 1.0     |
|  1      | Martes 01/12        |    + 0.9     |
|  2      | Miércoles 02/12     |    + 0.8     |
|  3      | Jueves 03/12        |    + 0.7     |
|  4      | Viernes 04/12       |    + 0.6     |
|  5      | Miércoles 9/12      |    + 0.5     |
|  6      | Jueves 10/12        |    + 0.4     |
|  7      | Viernes 11/12       |    + 0.3     |
|  8      | Lunes 14/12         |    + 0.2     |
|  9      | Martes 15/12        |    + 0.1     |
|  **10** | **Miércoles 16/12** |   **0.0**    |
|  11     | Jueves 17/12        | NOTA MÍNIMA  |

**Como indica la tabla, las bonificaciones se acaban el día martes 15 de diciembre, a las 23:59 hrs. Y el plazo para entregar se acaba el día miércoles 16 de diciembre, a las 23.59 hrs. Si un trabajo llega después de esa fecha y hora, obtiene nota mínima (1.0)**.

**La entrega se hace vía e-mail:**

- Escriban a felipe.cortez@ucl, con copia a pdelosri@uc.cl, meinfante@uc.cl y canauto@uc.cl

- Se recomienda que el asunto sea "ENTREGA FINAL PDP" 

- En el cuerpo del correo deben indicar la dirección de su repositorio y la dirección de su GitHub Page. 

**¡Si entrega en fin de semana, o feriado, la fecha de su entrega será el día hábil siguiente!** Por ejemplo, si envía su correo el sábado 5 de diciembre, a las 2 AM, se considerará que su entrega se hace el miércoles 9 (el día 5, no el día 4). De esta manera respetamos nuestros días libres y mantenemos el trabajo en los días hábiles.
