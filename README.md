# seeRtutoriales

Este paquete contiene una serie de tutoriales para aprender R ¡todo en español!, esto fue desarrollado como parte del **Programa de especialización en Data Science** organizado por la **Sociedad Ecuatoriana de Estadística, SEE**. 

## Pasos iniciales

**1.** Para utilizar este paquete requiere tener instalado R y RStudio además de tener instalados los paquetes básicos para manipulación de datos. Puede descargar y seguir paso a paso la guía de instalación de R y Rstudio desde [aquí](https://goo.gl/sKH4eY), en esta guía se detallan los paquetes a descargar.   

Puede ver un video explicativo [aquí](https://www.youtube.com/watch?v=1WXgaa2Spp0)   


**2** Este paquete está alojado en gitHub, para instalar paquetes desde GitHub se requiere tener instalada la librería `devtools`, para ello en R ejecute: `install.packages("devtools")`

**3** Para la correcta ejecución se requiere también el uso de los paquetes learnr y xtable, instale ambos mediante:     
- `install.packages("learnr")`    
- `install.packages("xtable")`    

**4** Instalar el paquete seeRtutoriales:


                       Para instalar seeRtutoriales desde GitHub ejecute:   
                       devtools::install_github("nestormontano/seeRtutoriales")


**5** Una vez instalado todo, puede empezar a ejecutar cada tutorial.



## Tutoriales contenidos:   
___________________________

Para ejecutar los tutoriales ejecute los comandos indicados debe usar el comando `learnr::run_tutorial()`

### Tutorial 1: Bases y manipulacion de datos

#### Ejecutar en R: 

`learnr::run_tutorial("1_ManipulacionData", package = "seeRtutoriales")`


#### Contenido
- Introducción a R
- Importar y entender datos
- Manipulacion de datos: Nivel basico
- Ordenar los datos (Tidy)
- Unir varios conjuntos de datos
- Aplicar funciones a columnas (map)




### Tutorial 2: Limpieza y valores perdidos

En construcción




# Mantenimiento y Licenciamiento
_____________________________________


El paquete se distribuye bajo licencia Creative Commons CC BY-NC-SA, el código actualizado puede ser descargado actualizado desde https://github.com/nestormontano/seeRtutoriales.

Sugerencias o correcciones puede hacerlas mediante GitHub o via mail a nestor.montano@gmail.com
