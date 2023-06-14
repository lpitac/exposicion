<p></p>
<h1 align="center"><img src="https://lpitac.github.io/exposicion/assets/img/captura_portada.svg" alt=""><p></p></h1>
<h3>La forma más sencilla de crear una exposición virtual a partir de una colección de objetos digitales y un CSV con sus metadatos.</h3>

<a href="#como">Cómo empezar</a> &ensp;&bull;&ensp; <a href="#tecnologias">Tecnologías</a> &ensp;&bull;&ensp; <a href="#licencia">metadatos</a> &ensp;&bull;&ensp; <a href="#licencia">Licencia</a>

# Exposición Virtual

Exposición Virtual es un fork de [CollectionBuilder](https://collectionbuilder.github.io/) una plantilla basada en [Jekyll](https://jekyllrb.com/), que permite crear un sitio web estático a partir de una colección de objetos digitales y un CSV con sus metadatos.
Este sitio web se puede alojar en cualquier carpeta compartida de la red (local o internet), en un servidor web básico o en GitHub.

## Mejoras implementadas
El principal objetivo 
 usando GitHub Actions).
 
<a name="como"></a>
## Cómo empezar
Para utilizar esta plantilla:

1- Prepara los metadatatos de tu colección siguiendo la plantilla de prueba publicada en [Google Sheets](https://docs.google.com/spreadsheets/d/1nN_k4JQB4LJraIzns7WcM3OXK-xxGMQhW1shMssflNM/edit?usp=sharing). 
	 La forma más sencilla de utilizarla es haciendo una copia que deberás guardar en una cuenta de Google Drive. De este modo podrás editarla en línea, lo cual te resultará muy sencillo ya que se ha optimizado para facilitar su uso (campos desplegables, relleno automático, ...)
2- Reune en una carpeta todos los objetos digitales descritos en el CSV.
3- Descarga [Fiador 1.0.](https://). 

----------
<a name="tecnologias"></a>
## Tecnologías empleadas 
### Tema de la plantilla 
El diseño del sitio web hace uso de [Bootstrap](https://getbootstrap.com/) un framework de código abierto que facilita la creación de interfaces web basadas en HTML, CSS y JavaScript.

### Visualizaciones
Para crear las distintas visualizaciones e interaciones sobre los objetos y sus metadatos se han empleado las siguientes bibliotecas JavaScript 

- Galería de imágenes: [Spotlight gallery](https://github.com/nextapps-de/spotlight)
- Cargador de imágenes: [lazysizes](https://github.com/aFarkas/lazysizes),
- Tablas: [DataTables](https://datatables.net/): plug-in para la biblioteca jQuery Javascript que permite crear tablas.
- Mapas: [Leafletjs](http://leafletjs.com/)
- Buscador frontend: [Lunr.js](https://lunrjs.com/)

<a name="metadatos"></a>
### Metadatos
Los metadatos utilizados de ejemplo cumplen los estándares [Schema.org](http://schema.org) y [Open Graph protocol](http://ogp.me/).

<a name="licencia"></a>
## Licencia
Exposición Virtual está publicada bajo licencia [Creative Commons Attribution-ShareAlike 4.0 International] (http://creativecommons.org/licenses/by-sa/4.0/), a excepción de las dependencias externas incluidas en el directorio `assets/lib`, que están cubiertas por sus licencias individuales. 
Tampoco abarca los objetos digitales utilizados como ejemplo. En cada uno de ellos se especifica, bajo el campo "Licencia" la licencia concreta aplicada.