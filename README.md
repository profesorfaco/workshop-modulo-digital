# PdP · Módulo Digital · 2021-1

### Código fuente para el desarrollo objetos digitales

**Para el trabajo grupal final del Módulo Digital, nos basaremos en lo desarrollado para el Módulo Gráfico**. De allí tomaremos:

1. [COLORES](https://github.com/profesorfaco/digital#1-colores)
2. [FUENTES TIPOGRÁFICAS](https://github.com/profesorfaco/digital#2-fuentes-tipogr%C3%A1ficas)
3. [GRÁFICOS (FIGURATIVO, NO FIGURATIVO Y MIXTO)](https://github.com/profesorfaco/digital#3-gr%C3%A1ficos-figurativo-no-figurativo-y-mixto)
4. [TEXTOS](https://github.com/profesorfaco/digital#4-textos)

Aprovechando tales elementos describiremos y programaremos una página web, tipo [landing page](https://es.wikipedia.org/wiki/P%C3%A1gina_de_aterrizaje). 

Para describir y programar esta página usaremos [Bootstrap](https://getbootstrap.com/), lo que nos facilitará trabajo con el 5. [CÓDIGO FUENTE](https://github.com/profesorfaco/digital#5-c%C3%B3digo-fuente).

Para que puedan escribir su código fuente, podrán usar uno de los siguientes editores:

- [Sublime Text](https://www.sublimetext.com/) 
- [Atom.io](https://atom.io/)
- [Brackets](http://brackets.io/) 

Estos editores les entregan "pistas" mientras van escribiendo, tal como hacen los editores de texto (que adelantan palabras o te indican las faltas de ortografía).

**Para la entrega grupal final deben utilizar un [repositorio de organización](https://git-scm.com/book/es/v2/GitHub-Gesti%C3%B3n-de-una-organizaci%C3%B3n) en [GitHub](https://github.com/) y aprovechar [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).**

En el repositorio de organización debe ser visible la contribución de cada integrante del grupo. Por esta razón, cada integrante del grupo debe tener su cuenta personal en GitHub.

**Veamos un ejemplo**: El proyecto Guemil tiene su [organización en GitHub](https://github.com/Guemil). Son 7 las personas que forman parte de esta organización. Si ingresan a cualquier repositorio, podrán ver quiénes han contribuido a su desarrollado. Si ingresan a [Crea_Guemil](https://github.com/Guemil/Crea_Guemil), encontrarán que allí han contribuido: [tucormamirez](https://github.com/tucoramirez), [fjgajardo](https://github.com/fjgajardo) y [profesorfaco](https://github.com/profesorfaco). Sólo 3 de 7. No hay aportes de cada integrante de la organización.

- - - - - - - - - - - - - - - - 

**Su trabajo grupal será evaluado con el uso de [una rúbrica](https://docs.google.com/spreadsheets/d/1syeC8V3ej8MmKgB1F4mXcNk7yjakgOjMSv8cVh6qeO8/edit?usp=sharing) que está disponible en la carpeta del Drive a la que todo el curso tiene acceso**.

La rúbrica evalúa la modificación grupal de una [plantilla](https://github.com/profesorfaco/digital/tree/main/plantilla) que incluye tres páginas HTML, un estilo CSS (que se aplica a dos de las tres páginas) y una carpeta con imágenes:

- [skeleton.html](https://profesorfaco.github.io/digital/plantilla/skeleton.html) → Página de prueba de contenidos (sin estilo)
- [surface.html](https://profesorfaco.github.io/digital/plantilla/surface.html) → Página de prueba de estilo (sin contenidos)
- [index.html](https://profesorfaco.github.io/digital/plantilla/index.html) → Página definitiva (con estilo y cotenidos)

- - - - - - - - - - - - - - - - 

**Para abordar el trabajo, conviene que los grupos auto-organicen el aprendizaje sobre colores, fuentes tipográficas, gráficos y textos en web; que un/a integrante se encargue de cada tema. Luego, si el grupos tiene 6 o 7 integrantes, quedan 2 o 3 que podrán trabajar exclusivamente en el código fuente.**

#### 1. COLORES 

1.1. Transformar sus colores para impresión (Pantone/CMYK) por equivalentes para pantalla (HEX/RGB) → https://www.pantone.com/color-finder/

1.2. Revisar el [*contrast ratio*](https://www.w3.org/TR/WCAG21/#contrast-minimum) de los colores transformados para asegurar la legibilidad. Corresponde ajustar aquellos colores que ofrezca un *contrast ratio* insuficiente para negro (#000000) o blanco (#FFFFFF) puestos en nivel de figura (Foreground) y fondo (Background) → https://webaim.org/resources/contrastchecker/

1.3. Una vez tengan los colores definitivos, podrán modificar las [variables CSS](https://developer.mozilla.org/es/docs/Web/CSS/--*) en el [style.css](https://profesorfaco.github.io/digital/plantilla/style.css) de su copia de la plantilla.

**Más información en:**

- *Simplified color theory for noobs* → https://www.instagram.com/p/CP-_DSMo4vA/
- *Understanding Web Accessibility Color Contrast Guidelines and Ratios* → https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/

#### 2. FUENTES TIPOGRÁFICAS 

2.1. Buscar las fuentes tipográficas en el catálogo de Google Fonts; en caso de no encontrarla(s), reemplácenla(s) por otra(s) disponible(s) en el mismo catálogo → https://fonts.google.com/

Es importanta considerar que:

> Siempre hay excepciones, siempre hay excusas para las sorpresas y los trucos. Pero tal vez podamos ponernos de acuerdo en que, en general, la tipografía puede realizar los siguientes servicios […] invitar al lector a entrar en el texto; mostrar el tenor y significado del texto; vincular el texto con otros elementos; [e] inducir un estado de enérgico reposo, que es la condición ideal para la lectura (Bringhurst, 2008:31)

2.2. Escoger una escala de cuerpos tipográficos que empice en un tamaño que permita inducir al estado de enérgico reposo en la lectura de los párrafos. Además de un tamaño para **párrafo** (normal), **párrafo destacado** (más grande de lo normal) y notas al margen (más pequeño de lo normal), pueden establecer tamaños para distintos niveles de encabezados (un máximo de 6, con 1 título y 5 subtítulos en distintos tamaños) → https://bootstrapcreative.com/bootstrap-text-sizes/

2.3. Una vez tengan los tamaños definitivos, podrán modificar el [style.css](https://profesorfaco.github.io/digital/plantilla/style.css) de su copia de la plantilla.

**Más información**

- *The Elements of Typographic Style Applied to the Web* → http://webtypography.net/
- *Typography Terms Cheat Sheet* → https://www.nngroup.com/articles/typography-terms-ux/

#### 3. GRÁFICOS (FIGURATIVO, NO FIGURATIVO Y MIXTO)

**3.1. gráficos figurativos (imágenes o ilustraciones)**: Crear tres versiones para cada una de las imágenes que utilizaron en la infografía para el módulo de diseño gráfico. Cada una de tales versiones tendrá que responder a *smartphone (small)*, *tablet (medium)* o *desktop (large)*.

Para crear estas versiones, y debido a la gran [variedad de pantallas con tamaños y resoluciones](http://screensiz.es/), no existen recetas infalibles. Todo es una apuesta. Pero podemos quedar en un lugar suficientemente seguro considerando los tamaños de ancho de pantalla que usa [Bootstrap](https://getbootstrap.com/docs/5.0/layout/breakpoints/) como referencia para sus cambios entre *smartphone (small)*, *tablet (medium)* y *desktop (large)*, que son, respectivamente: 576px, 768px y 992px.

Si ya tenemos un ancho para la imagen, nos falta un alto. En este punto podemos encontrar un lugar más seguro aprovechando [la relación de aspecto](https://es.wikipedia.org/wiki/Relaci%C3%B3n_de_aspecto) más probable; podría ser que una imagen que se vea a pantalla completa en *smartphone (small)* se acerque al formato Panavision vertical (2.39:1), mientras que una imagen que se vea a pantalla completa en *tablet (medium)* podría estar más cerca de la razón 3:2. Y podría ser que una imagen que se vea completa en *desktop (large)* esté más cerca del 16:9.

Y lo que queda por cuidar es el peso de la imagen, y para ello está [la optimización con formatos GIF, JPG o PNG](https://squoosh.app/), o hacer pruebas con el formato [WebP](https://developers.google.com/speed/webp). **Si descuidan el peso de las imágenes: Abusarán de la transferencia de datos en la conexión a Internet de cada visitante**. Cuando se abusa de la transferencia, la imagen no se carga rápido. ¿Qué tan rápido debería cargarse? Esto podría darles una idea:

- [Tienes 5 segundos](http://www.tienes5segundos.cl/) se llama un viejo clásico local sobre gestión de contenidos digitales.
- [5-Second Usability Test](https://www.nngroup.com/videos/5-second-usability-test/) se llama una técnica que permite evaluar la primera impresión de un sitio web. 

Una página web debería estar completamente cargada en 5 segundos → https://nbadiola.com/peso-ideal-fotografia-para-web/

**3.2. gráficos mixtos**: Este gráfico debe completarse con un trabajo en Illustrator o InkScape, a exportar como SVG. En ese trabajo deben utilizar un gráfico figurativo (de peso cuidado) en una capa de fondo y sobre ella dibujar algo no figurativo. Con esto pueden, por ejemplo, intervenir [una imagen satelital](https://graphics.reuters.com/CALIFORNIA-WILDFIRES/xegvboxrypq/index.html) o [un mapa](https://graphics.reuters.com/USA-WILDFIRES/WINE/bdwpkkmxmpm/index.html).

**3.3. gráficos no figurativos**: Este gráfico debe completarse con datos reales y la utilización de [Chart.js](https://www.chartjs.org/). El despliegue más adecuado de datos es lo que debe ayudarles a decidir entre: [Line chart](https://www.chartjs.org/docs/latest/charts/line.html), [Bar Chart](https://www.chartjs.org/docs/latest/charts/bar.html), [Radar Chart](https://www.chartjs.org/docs/latest/charts/radar.html), [Doughnut/Pie Charts](https://www.chartjs.org/docs/latest/charts/doughnut.html), [Polar Area Chart](https://www.chartjs.org/docs/latest/charts/polar.html), [Bubble Chart](https://www.chartjs.org/docs/latest/charts/bubble.html) o [Scatter Chart](https://www.chartjs.org/docs/latest/charts/scatter.html). 

#### 4. TEXTOS

4.1. Revisar la credibilidad del texto original → http://credibility.stanford.edu/guidelines/index.html

4.2. Establecer un tono de voz pertinente al mensaje → https://www.nngroup.com/articles/tone-of-voice-dimensions/

4.3. Editar el textos para su lectura en web → https://www.nngroup.com/articles/how-users-read-on-the-web/

**Más información en:**

- *Las 11 reglas de oro para escribir contenido en tu página web* → https://www.jimdo.com/es/blog/escribir-contenido-pagina-web/
- *Concise, SCANNABLE, and Objective: How to Write for the Web* → https://www.nngroup.com/articles/how-users-read-on-the-web/

#### 5. CÓDIGO FUENTE

Escribir una serie de descripciones o instrucciones en un lenguaje pertinente; en una página web, la descripción se hace habitualmente HTML y CSS, y la programación con JavaScript. A diseñadoras/es con interés por la gráfica, les conviene conocer SVG

- https://github.com/profesorfaco/digital/wiki/HTML
- https://github.com/profesorfaco/digital/wiki/CSS
- https://github.com/profesorfaco/digital/wiki/JavaScript
- https://github.com/profesorfaco/digital/wiki/SVG

- - - - - - - - - - - - - - - 

### La entrega se hace vía e-mail

- Envíe un e-mail a felipe.cortez@ucl con copia a pdelosri@uc.cl, meinfante@uc.cl y francisca.choy@uc.cl

- Se recomienda que el asunto de su e-mail sea "ENTREGA FINAL PDP" 

- En el cuerpo del correo deben indicar la URL del repositorio de la organización y también la URL de su GitHub Page. Noten las diferencias de ambas:

  - La URL del repositorio de la organización en GitHub puede verse así: https://github.com/Guemil/Guemil_Guidelines

  - La URL de su GitHub Page se puede ver así: https://guemil.github.io/Guemil_Guidelines/

En el ejemplo, **Guemil** es el nombre de la [organización en GitHub](https://git-scm.com/book/es/v2/GitHub-Gesti%C3%B3n-de-una-organizaci%C3%B3n), y **Guemil_Guidelines** es el nombre del repositorio dentro de la misma organización.

#### ¿Cuándo enviar el e-mail?

Cuentan con 10 días hábiles. Según la fecha de su entrega, podrán obtener bonificación:

| Día     | Fecha               | Bonificación |
|:-------:|:--------------------|:------------:|
|  1      | Lunes 05/07         |    + 1.0     |
|  2      | Martes 06/07        |    + 0.8     |
|  3      | Miércoles 07/07     |    + 0.6     |
|  4      | Jueves 08/07        |    + 0.4     |
|  5      | Viernes 09/07       |    + 0.2     |
|  6      | Lunes 12/07         |      0       |
|  7      | Martes 13/07        |      0       |
|  8      | Miércoles 14/07     |      0       |
|  9      | Jueves 15/07        |      0       |
|  10     | Viernes 16/07       |      0       |

> Como indica la tabla, las bonificaciones se acaban el día viernes 9 de junio, a las 23:59 hrs. **Pero pueden entregar hasta las 23.59 hrs. del viernes 16 de julio. Si un trabajo llega después de fecha y hora recién indicadas, obtiene nota mínima (1.0)**. 

El promedio del curso debe cerrarse el día Miércoles 21 de julio, por lo que el equipo docente contará sólo con un par de días hábiles para evaluar y promediar.

**¡A propósito de días hábiles! Si entrega en fin de semana (sábado 10 o domingo 11 de julio), la fecha de su entrega será el día hábil siguiente (lunes 12/07)**. De esta manera respetamos nuestros días libres y mantenemos el trabajo en los días hábiles.
