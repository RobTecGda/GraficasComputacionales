# GraficasComputacionales - Actividad Integradora 

## A01637335 - Roberto López Cisneros

Este repositorio contiene los archivos necesarios para simular el cruce de autos de 2 calles.

### Archivos:
* PDF con diagramas y descripción del entorno multiagentes: "Reporte Actividad Integradora.pdf"
* Código para generar la simulación: "FinalSolution.ipynb"
* Archivo html y JSON para la simulación gráfica: "index.html" y "testData.json"

### Instrucciones de ejecución:
El repositorio esta listo para su ejecución y deberá utilizarse un server. 
En caso de realizar cambios, realice lo siguiente:

* Simulación:
  * Ejecutar notebook FinalSimulation.ipynb, en donde se puede jugar con parametros.
  * El notebook genera un archivo Json para simular en el modelado gráfico.
  * En caso de querer cambiar la ubicación de salida, podría cambiar el path en la clase AvenueModel.
  * Si la salida no se guardará en Drive, debera comentar la parte de crear archivo Json.

* Modelado gráfico: 
  * En base al Json generado por la simulación, ejecutar el archivo html. 
  * De preferencia el archivo Json debe estar en la misma ubicación del html, junto con la carpeta assets.
  * En caso de agregar o cambiar modelos obj se debera cambiar el path dentro del html.
