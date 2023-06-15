<p></p>
<h1 align="center"><img src="https://lpitac.github.io/exposicion/assets/img/captura_portada.svg" alt=""><p></p></h1>
<h3 align="center">La forma más sencilla de crear una exposición virtual a partir de una colección de objetos digitales y un CSV con sus metadatos.</h3>

<h3 align="center"><a href="#como">Cómo empezar</a> &ensp;&bull;&ensp; <a href="#tecnologias">Tecnologías empleadas</a> &ensp;&bull;&ensp; <a href="#licencia">Metadatos</a> &ensp;&bull;&ensp; <a href="#licencia">Licencia de uso</a></h3>

# Exposición Virtual

_Exposición_ _Virtual_ es un _fork_ de [CollectionBuilder](https://collectionbuilder.github.io/) una plantilla basada en [Jekyll](https://jekyllrb.com/), que permite crear un sitio web estático a partir de una colección de objetos digitales y un CSV con sus metadatos.
Este sitio web se puede alojar en cualquier carpeta compartida de una red, en un servidor web básico (local o de internet) y en [GitHub](https://github.com/) (haciendo uso de [GitHub Actions Jekyll](https://jekyllrb.com/docs/continuous-integration/github-actions/) ).

Se puede ver en acción en 

# Fiador 1.0
_Fiador_ es un software libre escrito en Python que permite automatizar la creación del sitio web basándose en la plantilla _Exposición_ _Virtual_.

<h3>Exposición virtual de demostración:<p></p><a href="https://lpitac.github.io/exposicion/">https://lpitac.github.io/exposicion/ </a></h3>

<a name="como"></a>
## Cómo empezar
Hay dos formas de utilizar _Fiador_ junto con la plantilla _Exposición_ _Virtual_: 
- __Instalación__ __de__ __prueba__: utiliza los objetos digitales y el CSV con sus metadatos incluidos en la plantilla.
- __Instalación__ __personalizada__: permite establecer los objetos digitales y el CSV que se utilizarán para generar el sitio web.

### Instalación de prueba
Descarga, instala y ejecuta [Fiador 1.0.](https://) 

### Instalación personalizada
1. Prepara los __metadatatos__ de tu colección siguiendo la plantilla de prueba publicada en [Google Sheets](https://docs.google.com/spreadsheets/d/1nN_k4JQB4LJraIzns7WcM3OXK-xxGMQhW1shMssflNM/edit?usp=sharing). 
	 La forma más sencilla de utilizarla es haciendo una copia que deberás guardar en una cuenta de Google Drive. De este modo podrás editarla en línea, lo cual te resultará muy sencillo ya que se ha optimizado para facilitar su uso (campos desplegables, relleno automático, ...)
2. Reune en una carpeta todos los objetos digitales descritos en el CSV.
3. Descarga, instala y ejecuta [Fiador 1.0.](https://) 

---
<a name="tecnologias"></a>
## Tecnologías empleadas
### Creación del sitio web 
La generación de las páginas necesarias para construir la exposición virtual basada en __HTML__, __CSS__ y __JavaScript__ se lleva a cabo con [Jekyll](https://jekyllrb.com/).  

### Tema de la plantilla 
El diseño del sitio web hace uso de [Bootstrap](https://getbootstrap.com/) un framework de código abierto que facilita la creación de interfaces web basadas en __HTML__, __CSS__ y __JavaScript__.

### Bibliotecas JavaScript
Para crear las distintas visualizaciones e interaciones sobre los objetos y sus metadatos se han empleado las siguientes bibliotecas JavaScript: 

- __Galería de imágenes__: [Spotlight gallery](https://github.com/nextapps-de/spotlight)
- __Cargador de imágenes__: [lazysizes](https://github.com/aFarkas/lazysizes)
- __Tablas__: [DataTables](https://datatables.net/): plug-in para la biblioteca jQuery Javascript que permite crear tablas.
- __Mapas__: [Leafletjs](http://leafletjs.com/)
- __Buscador frontend__: [Lunr.js](https://lunrjs.com/)

<a name="metadatos"></a>
### Metadatos
Los metadatos utilizados de ejemplo cumplen los estándares [Schema.org](http://schema.org) y [Open Graph protocol](http://ogp.me/).

<a name="licencia"></a>
## Licencia
__Exposición__ __Virtual__ está publicada bajo licencia [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/), a excepción de las dependencias externas incluidas en el directorio `assets/lib`, que están cubiertas por sus licencias individuales. 
Tampoco abarca los objetos digitales utilizados como ejemplo. En cada uno de ellos se especifica, bajo el campo __"Licencia"__ la licencia concreta aplicada.

---
2023 - Lorena P.C.