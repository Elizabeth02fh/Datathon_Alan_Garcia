## **1era Datathon Datanilo - Análisis de los comentarios sobre la muerte de Alan García**
### **Contexto de la Datathon** 05/12/2024 - 08/12/2024

Los dataset proporcionados reúne comentarios de varios posts en Facebook publicados por el diario
"El Comercio", capturando opiniones y sentimientos en tiempo real, son datos cualitativos 
con las reacciones del público ante uno de los eventos más significativos de la política peruana 
el fallecimiento del ex presidente Alan García en 2019.

## **Pasos para la solución**

  + `Paso 1:` Comprensión de las fuentes de datos y su contenido.

  + `Paso 2:` Proceso de limpieza, Transformacion, Estandarización de datos con python
    
    *• Se descarga los dataset del drive, para luego realizar la importacion de los datasets con la libreria de pandas
    leemos los datasets.*
    
    *• Realizacion del Analisis Exploratorio de datos usando python, transformación de los campos como la de Fecha, se creo otras
    dos columnas de Hora y de Fecha, ya que no estaban en un formato adecuado.*
    
    *• Eliminacion de datos vacios, eliminacion de datos duplicados, imputacion de datos faltantes.*
    
    *• Estandarización de las encabezados de las columnas, se puso un nombre adecuado a los headers de cada de los dfs.*
    
    *• Se puso el tipo de datos adecuado a cada columna, como string o datetime, etc.*
    
    *• Finalmente se exportaron a formato csv.*
    
  + `Paso 3:` Importacion de los csv a Power BI.

  + `Paso 4:` Creación del modelo de datos.
<img src="https://github.com/Elizabeth02fh/Datathon_Alan_Garcia/blob/7d964b1c6cd291d492297beb471faed1488c2268/modelo_de_datos.JPG" alt="modelo_de_datos" width="700">

  + `Paso 5:` Portada o página de incio.
<img src="https://github.com/Elizabeth02fh/Datathon_Alan_Garcia/blob/99dcefc40c1eff6cf69dcf58e4778dc2ecd2e25c/portada.png" alt="portada.png" width="700">

  + `Paso 6:` Dashboard de Análisis de comentarios.
<img src="https://github.com/Elizabeth02fh/Datathon_Alan_Garcia/blob/a74db970952e43829ab2031df37392b607731169/dashboard.JPG" alt="dashboard.JPG" width="700">

**Technological tools:**

+ `Python:` EDA + transformations + Preprocessing 
+	`Visual Studio:` Entorno 
+	`Power BI:` Modelo de datos, Dashboard
