# Exposición Virtual

Exposición Virtual es un fork de [CollectionBuilder](https://collectionbuilder.github.io/) una plantilla basada en [Jekyll](https://jekyllrb.com/), que permite crear un sitio web estático a partir de una colección de objetos digitales y un CSV con sus metadatos.
Este sitio web se puede alojar en cualquier carpeta compartida de la red (local o internet), en un servidor web básico o en GitHub.

## Mejoras implementadas
El principal objetivo 
 usando GitHub Actions).

## Cómo utilizar esta plantilla

:

- Make your own copy of this template repository by clicking the green "Use this Template" button on GitHub (see [repository set up docs](https://collectionbuilder.github.io/cb-docs/docs/repository/)). This copy of the template is the starting point for your "project repository", i.e. the source code for your digital collection site!
- Prepare your collection metadata following the CB-CSV template (see our demo [metadata template on Google Sheets](https://docs.google.com/spreadsheets/d/1nN_k4JQB4LJraIzns7WcM3OXK-xxGMQhW1shMssflNM/edit?usp=sharing) and [metadata docs](https://collectionbuilder.github.io/cb-docs/docs/metadata/csv_metadata/)). Your metadata will include links to your digital files (images, pdfs, videos, etc) and thumbnails wherever they are hosted.
- Add your metadata as a CSV to your project repository's "_data" folder (see [upload metadata docs](https://collectionbuilder.github.io/cb-docs/docs/metadata/uploading/)).
- Edit your project's "_config.yml" with your collection information (see [site configuration docs](https://collectionbuilder.github.io/cb-docs/docs/config/)). Additional customization is done via a theme file, configuration files, CSS tweaks, and more--however, once your "_config.yml" is edited your site is ready to be previewed. 
- Generate your site using Jekyll! (see docs for how to [use Jekyll locally](https://collectionbuilder.github.io/cb-docs/docs/repository/generate/) and [deploy on the web](https://collectionbuilder.github.io/cb-docs/docs/deploy/))

Please feel free to ask questions in the main [CollectionBuilder discussion forum](https://github.com/CollectionBuilder/collectionbuilder.github.io/discussions).

----------

## Tecnologías empleadas 

### Tema de la plantilla 
El diseño del sitio web hace uso de [Bootstrap](https://getbootstrap.com/).

### Visualizaciones

- [DataTables](https://datatables.net/)
- [Leafletjs](http://leafletjs.com/)
- [Spotlight gallery](https://github.com/nextapps-de/spotlight)
- [lazysizes](https://github.com/aFarkas/lazysizes),
- [Lunr.js](https://lunrjs.com/)

### Metadatos
Los metadatos utilizados de ejemplo cumplen los estándares [Schema.org](http://schema.org) y [Open Graph protocol](http://ogp.me/).


## Licencia
Exposición Virtual está publicada bajo licencia [Creative Commons Attribution-ShareAlike 4.0 International] (http://creativecommons.org/licenses/by-sa/4.0/), a excepción de las dependencias externas incluidas en el directorio `assets/lib`, que están cubiertas por sus licencias individuales. 
Tampoco abarca los objetos digitales utilizados como ejemplo. En cada uno de ellos se especifica, bajo el campo "Licencia" la licencia concreta aplicada.