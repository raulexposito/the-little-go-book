## Acerca de ##

El Pequeño Libro de Go ([The Little Go Book](http://openmymind.net/The-Little-Go-Book/)) es un libro introductorio gratuito de Go.

El libro fue escrito por [Karl Seguin](http://openmymind.net), autor de:

* [Scaling Viki](http://openmymind.net/scaling-viki/)
* [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/) (versión [en español](https://github.com/raulexposito/the-little-redis-book)) 
* [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/)
* [Foundations of Programming](http://openmymind.net/FoundationsOfProgramming.pdf)

La traducción ha sido realizada por [Raúl Expósito](http://raulexposito.com/).

[Descarga el libro en PDF](https://github.com/raulexposito/the-little-go-book/raw/master/es/go.pdf).

## Licencia ##
El libro se distribuye libremente bajo la licencia [Attribution-NonCommercial-ShareAlike 4.0 International](<http://creativecommons.org/licenses/by-nc-sa/4.0/>).

## Formatos ##
El libro está escrito en [Markdown](http://daringfireball.net/projects/markdown/) y se ha convertido en PDF usando [Pandoc](http://johnmacfarlane.net/pandoc/).

La plantilla TeX hace uso de el [remarcador de sintaxis de Javascript de Lena Herrmann](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Los formatos de Kindle y ePub han sido creados usando [Pandoc](http://johnmacfarlane.net/pandoc/).

## Generación de los Libros ##
Los paquetes mencionados a continuación son para Ubuntu. Si usas otro SO o distribución los nombres deben ser similares.

### PDF

#### Dependencias

Paquetes:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

Tienes que tener instaladas [algunas fuentes](https://github.com/karlseguin/the-little-redis-book/blob/master/common/pdf-template.tex#L11).

O puedes cambiarlas por otras si quieres. Ten en cuenta que las fuentes pueden acarrear [problemas de generación](https://github.com/karlseguin/the-little-redis-book/issues/26).

#### Construcción

Ejecuta `make es/go.pdf`.

### ePub

#### Dependencias

Paquetes:

* `pandoc`

#### Construcción

Ejecuta `make es/go.epub`.

### Mobi

#### Dependencias

Paquetes:

* `pandoc`

Debes tener [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) instalado también.

#### Construcción

Ejecuta `make es/go.mobi`.

## Imagen del título ##

Se incluye un PSD de la imagen del título. La fuente utilizada es [Comfortaa](http://www.dafont.com/comfortaa.font).
