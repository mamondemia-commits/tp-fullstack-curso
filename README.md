# Proyecto: Character Counter
Este proyecto consiste en realizar el maquetado y estilizacion de un contador de caracteres en tiempo real. 

## Objetivos del proyecto
El objetivo principal del proyecto fue construir la maquetación semántica y estructura visual usando HTML y CSS, para luego continuar el proyecto con JavaScript.

## Tecnologias Utilizadas
* HTML5: Para armar la estructura y las secciones de la pagina de manera ordenada y organizada.
* CSS3: Se utilizó para estilizar el proyecto aportando fuentes, colores, orden visual. 
* Flexbox: Se uso para alinear de manera flexible, tanto vertical como horizontalmente, el header, los checboxes y las barras de las letras. 
* Grid: Fue elegido para acomodar las 3 "cards" facilmente.
* Google Fonts: Se utilizó para incluir la tipografia del proyecto. 

## Como se Organizó el HTML
Se estructuró el HTML utilizando etiquetas semanticas para que quede prolijo y ordenado:
* "<header>": Dentro de "header" se colocó el logo y nombre de la pagina, y un botón para cambiar el tema de claro a oscuro. 
* "<main>": Esta etiqueta se usó para  marcar el contenido principal y centrarlo en la pantalla. 
* "<section>": Fue utilizada para separar por secciones el contenido de la pagina. Cada una con su respectiva clase:
  * <section class="hero">: Contiene un "<h2>" y el "<textarea>" donde el usuario escribe su texto.
  * "<section class="checkboxes">": Agrupa los "checkboxes" de configuracion dentro de la etiqueta "<label>" para que sea mas accesible. Tambien cuenta con una etiqueta de "<p>" del tiempo estimado de lectura.
  * "<section class="results">": Contiene las tres tarjetas (".card-purple", ".card-orange", ".card-coral").
  * "<section class="letter-density">": En esta ultima seccion se encuentran las filas de las letras ordenadas en forma de lista usando la etiqueta "<meter>" para las barras, junto al "<button>"para ver mas.

## CSS
Para el diseño del proyecto en CSS se utilizó:
* Variables (":root"): Donde se guardo la paleta de colores utilizada a lo largo del trabajo. Se crearon las variables para ahorrar tiempo escribiendo codigo y para facilitar si en un futuro se quiere modificar un color especifico de la pagina.

# Dificultades
* Modificar el "<meter>": Al principio me costo cambiarle el estilo orginal (color verde) que por defecto traen las barras de progreso. Luego pude modificarlo investigando, y utilicé "::-webkit-meter-bar" y "::-webkit-meter-optimum-value" para modificarle el borde y agregarle el color rosa. 

# Capturas del Resultado Final
Aquí dejo las capturas del proyecto terminado: 
