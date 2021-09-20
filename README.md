# PdP · Módulo Digital · 2021-2

### Código fuente para el desarrollo objetos digitales

**Para el trabajo grupal final del Módulo Digital, nos basaremos en lo desarrollado para el Módulo Gráfico**. De allí tomaremos colores, fuentes tipográficas, textos y gráficos (figurativos, no figurativos y mixtos)

Aprovechando tales elementos describiremos y programaremos una página web tipo [landing page](https://es.wikipedia.org/wiki/P%C3%A1gina_de_aterrizaje). 

Para facilitar el trabajo con el código fuente de la página web, usaremos [Bootstrap](https://getbootstrap.com/).

Para escribir su código fuente, atendiendo a las convenciones de [Bootstrap](https://getbootstrap.com/), podrían usar uno de los siguientes editores:

- [Sublime Text](https://www.sublimetext.com/) 
- [Atom.io](https://atom.io/)
- [Brackets](http://brackets.io/) 

Estos editores les entregan "pistas" mientras van escribiendo, tal como hacen los editores de texto (que predicen palabras e indican faltas de ortografía).

**Para el trabajo grupal final del Módulo Digital, deben utilizar un [repositorio de organización](https://git-scm.com/book/es/v2/GitHub-Gesti%C3%B3n-de-una-organizaci%C3%B3n) en [GitHub](https://github.com/) y aprovechar [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).**

En el repositorio de organización debe ser visible la contribución de cada integrante del grupo. Por esta razón, cada integrante debe tener su cuenta personal en [GitHub](https://github.com/) (si no tiene una, ahora puede crearla; si ya tenía una, aprovéchela).

**Veamos un ejemplo de repositorio de organización y contribución visible**: El proyecto Guemil tiene su [organización en GitHub](https://github.com/Guemil). Son 7 las personas que forman parte de esta organización. Si ingresan a cualquier repositorio, podrán ver quiénes han contribuido a su desarrollado; si ingresan al repositorio [Crea_Guemil](https://github.com/Guemil/Crea_Guemil), encontrarán que allí han contribuido: [tucormamirez](https://github.com/tucoramirez), [fjgajardo](https://github.com/fjgajardo) y [profesorfaco](https://github.com/profesorfaco). Sólo 3 de 7. En tal caso, no hay contribución visible de cada integrante de la organización.

- - - - - - - - - - - - - - - - 

**Su trabajo grupal final del Módulo Digital será evaluado con [una rúbrica](https://docs.google.com/spreadsheets/d/1_C5YwIV5uTjMRf7zwd2ph5JR34Yar_F2nLSdmPbV2CQ/edit?usp=sharing) que está disponible en Google Drive**.

La rúbrica evalúa la modificación grupal de una [plantilla](https://github.com/profesorfaco/modulo-digital/tree/main/plantilla) que incluye dos páginas HTML, un estilo CSS y una carpeta con imágenes.

Si un grupo no usa la [plantilla](https://github.com/profesorfaco/modulo-digital/tree/main/plantilla) y entrega una página web cualquiera, se arriega a obtener nota mínima porque los criterios de la rúbrica no podrán aplicarse. 

- - - - - - - - - - - - - - - - 

**Para abordar el trabajo, conviene que los grupos se auto-organicen** considerando que corresponde resolver asuntos de colores, fuentes tipográficas, textos y gráficos; un/a integrantes puede encargarse de cada tema. Luego, si el grupos tiene 6 o 7 integrantes, quedan 2 o 3 que podrán responsabilizarse del desafío del código fuente.

En lo que sigue, se recomienda que cada responsable haga la lectura que le corresponda: Si decides responsabilizarte del color, lee sobre colores; si decides responsabilizarte de fuentes tipográficas, lee sobre fuentes tipográficas; y así hasta el quinto subtítulo).

#### 1. COLORES

Quien se responsabilice de los colores, tendrá que:

1.1. transformar sus colores para impresión (Pantone/CMYK) por equivalentes para pantalla (HEX/RGB) → https://www.pantone.com/color-finder/

1.2. revisar el [*contrast ratio*](https://www.w3.org/TR/WCAG21/#contrast-minimum) de los colores transformados para asegurar la legibilidad. Corresponde ajustar aquellos colores que ofrezca un *contrast ratio* insuficiente para negro (#000000) o blanco (#FFFFFF) puestos en nivel de figura (Foreground) y fondo (Background) → https://webaim.org/resources/contrastchecker/

1.3. modificar las [propiedades personalizadas](https://developer.mozilla.org/es/docs/Web/CSS/--*) en el [style.css](https://profesorfaco.github.io/digital/plantilla/style.css) de la correspondiente copia de plantilla.

**Más información en:**

- *Simplified color theory for noobs* → https://www.instagram.com/p/CP-_DSMo4vA/
- *Understanding Web Accessibility Color Contrast Guidelines and Ratios* → https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/

#### 2. FUENTES TIPOGRÁFICAS 

Quien se responsabilice de las fuentes tipográficas, tendrá que:

2.1. hacer una búsqueda en el [catálogo de Google Fonts](https://fonts.google.com/); en caso de no encontrarla aquellas fuentes usadas en el trabajo del módulo gráfico, tendrá que reemplazarlas por las disponibles de rasgos similares. 

2.2. escoger pesos que permitan reconocer la relevancia de los títulos e inducir a un estado de enérgico reposo en la lectura de los párrafos.

2.3. modificar la importación de las fuentes y su aplicación en el [style.css](https://profesorfaco.github.io/digital/plantilla/style.css) de la correspondiente copia de plantilla.

**Más información**

- *The Elements of Typographic Style Applied to the Web* → http://webtypography.net/
- *Typography Terms Cheat Sheet* → https://www.nngroup.com/articles/typography-terms-ux/

#### 3. TEXTOS

Quien se responsabilice de los textos, tendrá que:

3.1. revisar la credibilidad del texto original → http://credibility.stanford.edu/guidelines/index.html

3.2. establecer un tono de voz pertinente al mensaje → https://www.nngroup.com/articles/tone-of-voice-dimensions/

3.3. editar el textos para su lectura en web → https://www.nngroup.com/articles/how-users-read-on-the-web/

**Más información en:**

- *Las 11 reglas de oro para escribir contenido en tu página web* → https://www.jimdo.com/es/blog/escribir-contenido-pagina-web/
- *Concise, SCANNABLE, and Objective: How to Write for the Web* → https://www.nngroup.com/articles/how-users-read-on-the-web/

#### 4. GRÁFICOS (FIGURATIVO, NO FIGURATIVO Y MIXTO)

Quien(es) se responsabilice(n) de los gráficos tendrá(n) que multiplicar su trabajo por 3 tipos de gráficos distintos:

**4.1. gráficos figurativos (fotografías o ilustraciones)**: Crear tres versiones para responder a *smartphone (small)*, *tablet (medium)* o *desktop (large)*.

Para crear estas versiones, y debido a la gran [variedad de pantallas con tamaños y resoluciones](http://screensiz.es/), no existen recetas infalibles. Todo es una apuesta. Pero podemos quedar en un lugar suficientemente seguro considerando los tamaños de ancho de pantalla que usa [Bootstrap](https://getbootstrap.com/docs/5.0/layout/breakpoints/) como referencia para sus cambios entre *smartphone (small)*, *tablet (medium)* y *desktop (large)*, que son, respectivamente, 576px, 768px y 992px.

Si ya tenemos un ancho para la imagen, nos falta un alto. En este punto podemos encontrar un lugar más seguro aprovechando [la relación de aspecto](https://es.wikipedia.org/wiki/Relaci%C3%B3n_de_aspecto) más probable; podría ser que una imagen que se vea a pantalla completa en *smartphone (small)* sea vertical, mientras que una imagen que se vea a pantalla completa en *tablet (medium)* es horizontal, pero menos ancha que aquella que se vea en *desktop (large)*.

Y lo que queda por cuidar es el peso de la imagen, y para ello está [la optimización con formatos JPG, PNG o GIF](https://squoosh.app/), o hacer pruebas con el formato [WebP](https://developers.google.com/speed/webp). **Consideren que descuidar el peso de las imágenes es abusar de la transferencia de datos en la conexión a Internet de cada visitante**. Cuando se abusa de la transferencia, la imagen no se carga rápido. ¿Qué tan rápido debería cargarse? Esto podría darles una idea:

- [Tienes 5 segundos](http://www.tienes5segundos.cl/) se llama un viejo clásico local sobre gestión de contenidos digitales.
- [5-Second Usability Test](https://www.nngroup.com/videos/5-second-usability-test/) se llama una técnica que permite evaluar la primera impresión de un sitio web. 

Una página web debería estar completamente cargada en 5 segundos → https://nbadiola.com/peso-ideal-fotografia-para-web/

**4.2. gráficos mixtos**: Este gráfico debe completarse con un trabajo en Illustrator o InkScape, a exportar como SVG. En ese trabajo deben utilizar un gráfico figurativo en una capa y sobre ella tendrán que dibujar algo no figurativo. Con esto pueden, por ejemplo, intervenir [una imagen capturada por un satélite](https://graphics.reuters.com/CALIFORNIA-WILDFIRES/xegvboxrypq/index.html).

**4.3. gráficos no figurativos**: Este gráfico debe completarse con datos reales y la utilización de [Chart.js](https://www.chartjs.org/). El despliegue más adecuado de datos es lo que debe ayudarles a decidir entre: [Line chart](https://www.chartjs.org/docs/latest/charts/line.html), [Bar Chart](https://www.chartjs.org/docs/latest/charts/bar.html), [Radar Chart](https://www.chartjs.org/docs/latest/charts/radar.html), [Doughnut/Pie Charts](https://www.chartjs.org/docs/latest/charts/doughnut.html), [Polar Area Chart](https://www.chartjs.org/docs/latest/charts/polar.html), [Bubble Chart](https://www.chartjs.org/docs/latest/charts/bubble.html) o [Scatter Chart](https://www.chartjs.org/docs/latest/charts/scatter.html). 

#### 5. CÓDIGO FUENTE

Quienes se responsabilicen del código fuente tendrán que editar una serie de descripciones e instrucciones en el lenguaje pertinente. 

Recuerden que en una página web la descripción se hace habitualmente HTML y CSS, y la programación con JavaScript. Además, a diseñadoras/es con interés por la gráfica, les conviene conocer SVG:

- https://github.com/profesorfaco/modulo-digital/wiki/HTML
- https://github.com/profesorfaco/modulo-digital/wiki/CSS
- https://github.com/profesorfaco/modulo-digital/wiki/JavaScript
- https://github.com/profesorfaco/modulo-digital/wiki/SVG

- - - - - - - - - - - - - - - 

### La entrega se hace vía e-mail

- Sólo un/a integrante del grupo debe enviar un e-mail a felipe.cortez@ucl **con copia a** pdelosri@uc.cl, ffblumel@uc.cl y francisca.choy@uc.cl

- Se recomienda que el asunto de su e-mail sea "ENTREGA DIGITAL PDP" 

- En el cuerpo del correo tiene que indicar la URL del repositorio de la organización y la URL de su GitHub Page. Noten las diferencias de ambas:

  - La URL del repositorio de la organización en GitHub puede verse así: https://github.com/Guemil/Guemil_Guidelines

  - La URL de su GitHub Page se puede ver así: https://guemil.github.io/Guemil_Guidelines/

En el ejemplo, **Guemil** es el nombre de la [organización en GitHub](https://git-scm.com/book/es/v2/GitHub-Gesti%C3%B3n-de-una-organizaci%C3%B3n), y **Guemil_Guidelines** es el nombre del repositorio dentro de la misma organización.

#### ¿Cuándo enviar el e-mail?

Cuentan con 10 días hábiles. Según la fecha de su entrega, podrán obtener bonificación:

| Día     | Fecha               | Bonificación |
|:-------:|:--------------------|:------------:|
|  1      | Lunes 04/10         | + 0.5 |
|  2      | Martes 05/10        | + 0.5 |
|  3      | Miércoles 06/10     | + 0.5 |
|  4      | Jueves 07/10        | + 0.5 |
|  5      | Viernes 08/10       | + 0.5 |
|  6      | Lunes 11/10         | 0 |
|  7      | Martes 12/10        | 0 |
|  8      | Miércoles 13/10     | 0 |
|  9      | Jueves 14/10        | 0 |
|  10     | Viernes 15/10       | 0 |

Como indica la tabla, las bonificaciones se acaban el día viernes 8 de octubre (a las 23:59 hrs.). **Pero pueden entregar hasta las 23.59 hrs. del viernes 15 de octubre. Si un trabajo llega después de fecha y hora recién indicadas, obtiene nota mínima (1.0)**. 

**Si entregan en fin de semana (sábado 9 o domingo 10 de octubre), la fecha de su entrega será el día hábil siguiente (lunes 11/10)**. De esta manera mantenemos el trabajo en los días hábiles, descansamos en fin de semana y cuidamos nuestra salud mental.
