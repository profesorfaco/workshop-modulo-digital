# Procesos de Producción | Módulo Digital | 2020-2

### Front End | Código fuente desde el diseño

Partamos con una analogía: 

Se ofrece puesto de trabajo en una empresa japonesa. Solo se requiere dominio del inglés. Tu lengua materna es el castellano, y dominas bien en inglés. 

¿Cómo te iría en ese trabajo si es que, además de inglés, supieras algo de japonés? ¿Mejor, igual o peor? ¿Por qué?

Agreguemos una cita:

> Los objetos digitales aparecen ante los usuarios humanos como seres coloridos y visibles. **Al nivel de la programación son archivos de texto**; en el sistema operativo son códigos binarios; a nivel de las tarjetas de circuitos, son señales generadas por los valores del voltaje y la operación de entradas lógicas (Hui, 2017: 88)

Mezclemos la analogía y la cita: 

A nivel de programación, los objetos digitales son archivos de texto. Como archivos de texto, se escriben. Ahora, cambiemos el dominio del japonés escrito por el dominio de algún lenguaje de descripción o programación de objetos digitales; ya comprenderás que no corresponde desalentarse si es que no escribes este tercer idioma mejor que un nativo al que se le exige escribrirlo, todos los días, de la mejor manera posible. Domina de la mejor manera posible tu lengua materna, apóyate en la lengua que te exijan, y, si viene al caso, aprovecha la tercera.

- - - - - - - - - - 

Nos basaremos en el trabajo desarrollado para el módulo gráfico. De allí tomaremos:

1. colores
2. fuentes
3. imágenes
4. texto

- - - - - - - - - - - - - - - - 

### 1. Colores 

1.1. Cambiar sus colores para impresión (Pantone) por colores para pantalla (HEX/HTML) → https://www.pantone.com/color-finder/

1.2. Revisar el *contrast ratio* para asegurar la legibilidad → https://webaim.org/resources/contrastchecker/

1.3. Ajustar aquellos colores que no ofrecen un *contrast ratio* suficiente → https://www.w3.org/TR/WCAG21/#contrast-minimum

> A [contrast ratio](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html) of 3:1 is the minimum level recommended by ISO-9241-3 and ANSI-HFES-100-1988 for standard text and vision. The 4.5:1 ratio is used in this provision to account for the loss in contrast that results from moderately low visual acuity, congenital or acquired color deficiencies, or the loss of contrast sensitivity that typically accompanies aging.

1.4. Una vez tengan los colores definitivos, podrán aprovechar las variables CSS para aplicarlos en una versión digital, interactiva y dinámica de su fanzine → [https://developer.mozilla.org/es/docs/Web/CSS/--*](https://developer.mozilla.org/es/docs/Web/CSS/--*)

**Más información en:**

- *¿Cuáles son los códigos de color de HTML?* → https://htmlcolorcodes.com/es/

- *Understanding Web Accessibility Color Contrast Guidelines and Ratios* → https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/
 

### 2. Fuentes tipográficas

Buscarlas en Google Fonts - https://fonts.google.com/

Seleccionar Jerarquías - https://bootstrapcreative.com/bootstrap-text-sizes/

### 3. Imágenes

Ajustarlas a tres versiones – *smartphone (small)*, *tablet (medium)* y *desktop (large)*. Para estos ajustes, y debido a la gran [variedad de dispositivos y respectivas pantallas existentes](http://screensiz.es/), no podemos contar con un tamaño único, como "recomendación infalible".

Guardarlas en JPG, GIF o PNG, con atención a los pesos resultantes – https://nbadiola.com/peso-ideal-fotografia-para-web/

### 4. Texto

Revisarlos en función de la lectura en web - https://www.jimdo.com/es/blog/escribir-contenido-pagina-web/
