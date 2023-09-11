<p></p>
<img src="https://lpitac.github.io/exposicion/assets/img/captura_portada_1.svg">

> <h3 align="center">La forma más sencilla de crear una exposición virtual a partir de una colección de objetos digitales y un CSV con sus metadatos.</h3>

<h3 align="center"><a href="#demo">Demo</a> &ensp;&bull;&ensp; <a href="#como">Cómo empezar</a> &ensp;&bull;&ensp; <a href="#tecnologias">Tecnologías empleadas</a> &ensp;&bull;&ensp; <a href="#licencia">Metadatos</a> &ensp;&bull;&ensp; <a href="#licencia">Licencia</a></h3>

# Exposición Virtual

__Exposición__ __Virtual__ es un _fork_ de [CollectionBuilder-CSV](https://collectionbuilder.github.io/), una __plantilla__ basada en [Jekyll](https://jekyllrb.com/) que permite crear un sitio web estático a partir de una colección de objetos digitales y un CSV con sus metadatos.
Este sitio web se puede alojar en un servidor web básico (local o de internet) o en [GitHub](https://github.com/) (haciendo uso de [GitHub Actions Jekyll](https://jekyllrb.com/docs/continuous-integration/github-actions/) ).

# Fiador

| ![Logo Fiador](https://github.com/lpitac/exposicion/blob/main/assets/img/logo_fiador.svg) | [Fiador](https://github.com/lpitac/fiador) es un software libre escrito en [Python](https://www.python.org) que permite automatizar la creación del sitio web, listo para publicarse, basándose en la plantilla ___Exposición Virtual___. |
|---|---|
<div align="center">
  <h3>
    <img src="https://github.com/lpitac/fiador/blob/main/iconos/descargar.png" alt="Icono de Descargar" style="vertical-align: middle;">
    <a href="https://purl.org/fiador/exe">Descargar Fiador</a>
  </h3>
</div>

<a name="demo"></a>
# Demo
<h3 align="center">Exposición virtual de demostración</h3> 
<img src="https://github.com/lpitac/exposicion/blob/main/assets/img/captura_portada.svg">
<h3 align="center"><a href="https://lpitac.github.io/exposicion/" target="_blank">https://lpitac.github.io/exposicion/</a></h3>

----
<a name="como"></a>
# Cómo empezar
[__Fiador 1.0__](https://purl.org/fiador/exe) ofrece tres funcionalidades:
1. Generar una exposición.
2. Editarla.
3. Abrirla.

<h1 align="center"><img src="https://github.com/lpitac/fiador/blob/main/capturas/ventana_ppal_fiador.png"></h1>

## Generar una exposición
Hay dos formas de utilizar [__Fiador 1.0__](https://purl.org/fiador/exe) junto con la plantilla [___Exposición Virtual___](https://github.com/lpitac/exposicion): 
1. __Exposición de prueba__: utiliza __los objetos digitales__ y el __CSV__ con sus metadatos incluidos en la __plantilla__.
2. __Exposición personalizada__: permite __definir los objetos digitales y el CSV__ que se utilizarán para generar el sitio web. 

En ambos casos podrás editar los datos posteriormente.

<p align="center"><img src="https://github.com/lpitac/fiador/blob/main/capturas/ventana_generar_expo.png"></p>

### | Opción 1 | Exposición de prueba
1. Descarga y ejecuta [__Fiador 1.0__](https://purl.org/fiador/exe).
2. Pulsa sobre el botón __"Generar exposición"__.
3. Pulsa sobre el botón __"Exposición de prueba"__.
4. Indica el __directorio__ donde deseas albergar los archivos de la exposición.
5. Pulsa sobre el botón __"Generar"__.

El proceso puede tardar __varios minutos__ en completarse. Una vez listo, se mostrará el mensaje __"¡Exposición generada correctamente!"__. 

<p align="center"><img src="https://github.com/lpitac/fiador/blob/main/capturas/ventana_ok.png"></p>

Al pulsar sobre el botón __"Ok"__ la exposición se abrirá automáticamente en una ventana del navegador.

> <h3 align="center">¡Listo! Ya puedes navegar a través de la exposición web generada.</h3>

<p></p>

### | Opción 2 | Exposición personalizada
1. Prepara los __metadatatos__ de tu colección en formato __CSV__ siguiendo la __plantilla__ __de__ __prueba__ publicada en [Google Sheets](https://docs.google.com/spreadsheets/d/1nN_k4JQB4LJraIzns7WcM3OXK-xxGMQhW1shMssflNM/edit?usp=sharing). | Wiki -[¿Cómo utilizar la plantilla de prueba](https://github.com/lpitac/fiador/wiki/Metadatos) |
2. Reúne en una carpeta todos los __objetos__ __digitales__ __descritos__ en el __CSV__. | Wiki - [Formatos compatibles](https://github.com/lpitac/fiador/wiki/Objetos-digitales) |
3. Descarga y ejecuta [__Fiador 1.0__](https://purl.org/fiador/exe) 
4. Pulsa sobre el botón __"Generar exposición"__.
5. Pulsa sobre el botón __"Exposición personalizada"__.
	- Selecciona el __directorio__ donde deseas albergar los archivos de la exposición.
	- Selecciona el __directorio__ donde se encuentra el __CSV__ con los __metadatos__.
	- Selecciona el __directorio__ donde se encuentran los __objetos digitales__.
	- Cubre el resto de parámetros solicitados (__título__, __descripción__, ...).
8. Pulsa sobre el botón __"Generar"__.

El proceso puede tardar __varios minutos__ en completarse. Una vez listo, se mostrará el mensaje __"¡Exposición generada correctamente!"__. 

<p align="center"><img src="https://github.com/lpitac/fiador/blob/main/capturas/ventana_ok.png"></p>

Al pulsar sobre el botón __"Ok"__ la exposición se abrirá automáticamente en una ventana del navegador.

> <h3 align="center">¡Listo! Ya puedes navegar a través de la exposición web generada.</h3>

<p></p>



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
__Exposición__ __Virtual__ está publicada bajo licencia [MIT](https://opensource.org/license/mit/), a excepción de las bibliotecas incluidas en el directorio `assets/lib`, que están cubiertas por sus licencias individuales. 
Tampoco abarca los objetos digitales utilizados como ejemplo. En cada uno de ellos se especifica, bajo el campo __"Licencia"__ la licencia concreta aplicada.

---
2023 - Lorena P.C.
