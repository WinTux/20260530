# Instalación de R
De https://www.r-project.org
```bash
apt search "^r-.*" | sort
sudo apt install r-base r-base-dev
sudo apt install libpoppler-cpp-dev
sudo apt install libfontconfig1-dev libfreetype6-dev
```
# Instalación de R-Studio
De https://posit.co/download/rstudio-desktop
```bash
sudo apt install ./rstudio-2026.05.0-218-amd64.deb
```
# Desde R studio
- Cuadrante inf-der -> paquetes -> instalar -> bibliometrix

- Creo un proyecto y archivo principal.R
```bash
rm(list = ls(all =TRUE))
graphics.off()
system("clear")

library(shiny)

### BIBLIOMETRICS ###
library(bibliometrix)
biblioshiny()
```
Se ejecuta con
```bash
source("principal.R")
```
# ejemplo de uso
Ej desde la página local:
Menu lateral izquierdo -> Data -> pubmed -> 

# Software adicional (solo para Windows)
- https://harzing.com/resources/publish-or-perish/windows

# Enlaces de interés sobre investigación
- https://www.scimagojr.com/journalrank.php
- https://dm.ageditor.ar/index.php/dm/article/view/26/320

## APA
El siguiente enlace contiene plantillas y ejemplos, tanto para estudiantes como profesionales, acerca del uso correcto de APA
- https://apastyle.apa.org/style-grammar-guidelines/paper-format/sample-papers
