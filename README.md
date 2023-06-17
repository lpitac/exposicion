<p></p>
<img src="https://lpitac.github.io/exposicion/assets/img/captura_portada_1.svg">

> <h3 align="center">La forma más sencilla de crear una exposición virtual a partir de una colección de objetos digitales y un CSV con sus metadatos.</h3>

<h3 align="center"><a href="#demo">Demo</a> &ensp;&bull;&ensp; <a href="#como">Cómo empezar</a> &ensp;&bull;&ensp; <a href="#tecnologias">Tecnologías empleadas</a> &ensp;&bull;&ensp; <a href="#licencia">Metadatos</a> &ensp;&bull;&ensp; <a href="#licencia">Licencia</a></h3>

# Exposición Virtual

__Exposición__ __Virtual__ es un _fork_ de [CollectionBuilder](https://collectionbuilder.github.io/), una __plantilla__ basada en [Jekyll](https://jekyllrb.com/) que permite crear un sitio web estático a partir de una colección de objetos digitales y un CSV con sus metadatos.
Este sitio web se puede alojar en cualquier carpeta compartida de una red, en un servidor web básico (local o de internet) y en [GitHub](https://github.com/) (haciendo uso de [GitHub Actions Jekyll](https://jekyllrb.com/docs/continuous-integration/github-actions/) ).

# Fiador 1.0
[__Fiador 1.0__](https://udcgal-my.sharepoint.com/:u:/g/personal/l_pitac_udc_es/EZV8a3fDB11MjyJX_hW9j4kBonbKsP6gluycy_odu1MKQA?e=jGuWOX) es un software libre escrito en [Python](https://www.python.org) que permite automatizar la creación del sitio web, listo para publicarse, basándose en la plantilla ___Exposición Virtual___.

<h3 align="center"><a href="https://udcgal-my.sharepoint.com/:u:/g/personal/l_pitac_udc_es/EZV8a3fDB11MjyJX_hW9j4kBonbKsP6gluycy_odu1MKQA?e=jGuWOX">| Descargar Fiador 1.0 |</a></h3>

<a name="demo"></a>
# Demo
<h3 align="center">Exposición virtual de demostración</h3> 
<img src="https://github.com/lpitac/exposicion/blob/main/assets/img/captura_portada.svg" alt="">
<h3 align="center"><a href="https://lpitac.github.io/exposicion/" target="_blank">https://lpitac.github.io/exposicion/</a></h3>

----
<a name="como"></a>
# Cómo empezar
Hay dos formas de utilizar la plantilla ___Exposición Virtual___ junto con [__Fiador 1.0__](https://udcgal-my.sharepoint.com/:u:/g/personal/l_pitac_udc_es/EZV8a3fDB11MjyJX_hW9j4kBonbKsP6gluycy_odu1MKQA?e=jGuWOX): 
1. __Instalación de prueba__ : utiliza __los objetos digitales__ y el __CSV__ con sus metadatos incluidos en la __plantilla__.
2. __Instalación personalizada__: permite __definir los objetos digitales y el CSV__ que se utilizarán para generar el sitio web.

## | Opción 1 | Exposición de prueba
1. Descarga y ejecuta el instalador de [__Fiador 1.0__](https://udcgal-my.sharepoint.com/:u:/g/personal/l_pitac_udc_es/EZV8a3fDB11MjyJX_hW9j4kBonbKsP6gluycy_odu1MKQA?e=jGuWOX).
2. Pulsa sobre el botón __"Exposición de prueba"__.
3. Indica el __directorio__ donde deseas albergar los archivos de la exposición.
4. Pulsa sobre el botón __"Generar"__.

El proceso puede tardar varios minutos en completarse. Una vez listo, se mostrará el mensaje __"Exposición creada correctamente"__. 

Al pulsar sobre el botón __"Ok"__ se abrirá automáticamente una ventana del navegador predeterminado en la página de inicio del sitio web generado y se creará un acceso directo a __Fiador__ en el Escritorio de tu equipo.

> <h3 align="center">¡Listo! Ya puedes navegar a través de la exposición web generada.</h3>


## | Opción 2 | Exposición personalizada
1. Prepara los __metadatatos__ de tu colección en formato __CSV__ siguiendo la __plantilla__ __de__ __prueba__ publicada en [Google Sheets](https://docs.google.com/spreadsheets/d/1nN_k4JQB4LJraIzns7WcM3OXK-xxGMQhW1shMssflNM/edit?usp=sharing). 
> Lo más recomendable es que hagas una __copia de esta plantilla__ y la guardes en tu cuenta de __Google Drive__. De este modo podrás editarla en línea, lo cual simplifica el proceso ya que se ha optimizado para facilitar su uso (campos desplegables, relleno automático, ...). Una vez editada, descárgala en formato __CSV__ a tu equipo.
2. Reune en una carpeta todos los __objetos__ __digitales__ __descritos__ en el __CSV__.
3. Descarga y ejecuta el instalador de [__Fiador 1.0__](https://udcgal-my.sharepoint.com/:u:/g/personal/l_pitac_udc_es/EZV8a3fDB11MjyJX_hW9j4kBonbKsP6gluycy_odu1MKQA?e=jGuWOX) 
4. Pulsa sobre el botón __"Exposición personalizada"__.
3. Indica el __directorio__ donde deseas albergar los archivos de la exposición.
4. Cubre el resto de parámetros solicitados (__título__, __subtítulo__ y __descripción__ de la exposición).
5. Pulsa sobre el botón __"Generar"__.

El proceso puede tardar varios minutos en completarse. Una vez listo, se mostrará el mensaje __"Exposición creada correctamente"__. 

Al pulsar sobre el botón __"Ok"__ se abrirá automáticamente una ventana del navegador predeterminado en la página de inicio del sitio web generado y se creará un acceso directo a __Fiador__ en el Escritorio de tu equipo.

> <h3 align="center">¡Listo! Ya puedes navegar a través de la exposición web generada.</h3>


----
<a name="tecnologias"></a>
# Tecnologías empleadas
La generación de las páginas necesarias para construir la exposición virtual se basa en __HTML__, __CSS__ y __JavaScript__ y se lleva a cabo con [Jekyll](https://jekyllrb.com/).  

## Tema de la plantilla 
El diseño del sitio web hace uso de [Bootstrap](https://getbootstrap.com/) un framework de código abierto que facilita la creación de interfaces web basadas en __HTML__, __CSS__ y __JavaScript__.

## Bibliotecas JavaScript
Para crear las distintas visualizaciones e interaciones sobre los objetos y sus metadatos se emplean las siguientes bibliotecas JavaScript: 

- __Galería de imágenes__: [Spotlight gallery](https://github.com/nextapps-de/spotlight)
- __Cargador de imágenes__: [lazysizes](https://github.com/aFarkas/lazysizes)
- __Tablas__: [DataTables](https://datatables.net/)
- __Mapas__: [Leafletjs](http://leafletjs.com/)
- __Buscador frontend__: [Lunr.js](https://lunrjs.com/)

<a name="metadatos"></a>
### Metadatos
Los metadatos utilizados de ejemplo cumplen los estándares [Schema.org](http://schema.org) y [Open Graph protocol](http://ogp.me/).

---
<a name="licencia"></a>
# Licencia
__Exposición__ __Virtual__ está publicada bajo licencia [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/), a excepción de las bibliotecas incluidas en el directorio `assets/lib`, que están cubiertas por sus licencias individuales. 
Tampoco abarca los objetos digitales utilizados como ejemplo. En cada uno de ellos se especifica, bajo el campo __"Licencia"__ la licencia concreta aplicada.

---
2023 - Lorena P.C.