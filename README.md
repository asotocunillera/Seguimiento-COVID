# Seguimiento COVID19

Aplicación en VBA de Excel para realizar un seguimiento del avance del coronavirus en España.

Los datos son extraídos de la API [covid19tracking](https://covid19tracking.narrativa.com/es/spain/api.html "covid19tracking") realizada por el grupo  [Narrativa](https://www.narrativa.com/es/inicio/ "Narrativa") (info@narrativa.com) a partir de los datos recopilados por diferentes fuentes oficiales como:
- [Johns Hopkins University](https://systems.jhu.edu/research/public-health/ncov/ "Johns Hopkins University")
- [Ministerio de Sanidad](https://www.mscbs.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov/situacionActual.htm "Ministerio de Sanidad")

Al abrir el libro, automáticamente se comprueba si existen nuevos datos oficiales con respecto a los últimos guardados en el fichero `SegumientoCovid.xlsm`

En la hoja *General* del fichero, se muestra un gráfico interactivo para ver un resumen de los confimrados y muertes totales, o por comunidad, en función del día seleccionado.

![](https://github.com/asotocunillera/Seguimiento-COVID/blob/master/img/General.PNG)

En la hoja *Gráficos* del fichero, se incluye un gráfico interactivo de las diferentes variables extraídas de la [API](https://covid19tracking.narrativa.com/es/spain/api.html "covid19tracking") del grupo [Narrativa](https://www.narrativa.com/es/inicio/ "Narrativa")

![](https://github.com/asotocunillera/Seguimiento-COVID/blob/master/img/Graficos.PNG)

## Autor
Realizado por Álvaro Soto, asotocunillera@gmail.com
