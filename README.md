# Trabajo práctico 3  

### Elaborado por: Luis Carlos Gómez y Marget Aracelly Martínez.

Se trabajó con datos de presencia de felinos de 3 especies (Puma, Pantera y Leopardo), en las distintas Áreas Silvestres Protegidas (ASP) del país. Para la realización de la tabla y el gráfico se estuvo trabajando con la biblioteca *plotly*, mientras que para la realización de la cartografía se utilizó *folium* y sus distintas herramientas adicionales. 

Para trabajar con los datos, previsamente se tuvo que modificar el archivo *felinos.csv* con el fin de eliminar las horas de la fila de fechas, esto porque no daba resultados favorables. Por último, en los "popup" del mapa en la capa de felinos, en muchos de los puntos no se despliegan datos debido a que en la columna de localidad habían muchos datos vacíos. Sin embargo, podemos ver en la imagen #3 que el método empleado sí permite desplegar la información solicitada. 

![Popup en la capa de ASP](https://github.com/margetmartinez/Tarea03-Felinos_en_CostaRica/blob/main/Popup%20ASP.png)  
**Imagen 1.** Popup en ASP. 

![Popup de felinos](https://github.com/margetmartinez/Tarea03-Felinos_en_CostaRica/blob/main/Popup%20Felinos%201.png)  
**Imagen 2.** Popup capa felinos

![Popup felinos con todos los datos](https://github.com/margetmartinez/Tarea03-Felinos_en_CostaRica/blob/main/Popup%20Felinos%202.png)   
**Imagen 3.** Popup capa felinos con todos los datos.

[Enlace de NBVIEWER](https://nbviewer.org/github/margetmartinez/Tarea03-Felinos_en_CostaRica/blob/main/Tarea03Mar_y_Luis.1.ipynb)

Los datos fueron tomados de: [Registros de presencia de felinos de Costa Rica, agrupados por la Infraestructura Mundial de Información en Biodiversidad (GBIF).](https://www.gbif.org/occurrence/download/0141580-220831081235567) y [Áreas silvestres protegidas (ASP) de Costa Rica, publicadas por el Sistema Nacional de Áreas de Conservación (Sinac) en el Sistema Nacional de Información Territorial (SNIT).](https://www.snitcr.go.cr/ico_servicios_ogc_info?k=bm9kbzo6NDA=&nombre=SINAC)
