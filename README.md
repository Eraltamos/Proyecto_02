  
  

# <center><small>***Analisis del Acceso Fijo a Internet en Argentina***</small></center>  

# <center><small>***Data Analytics***</small></center>  

Argentina es uno de los paises con mayor desarrollo de telecomunicaciones siendo este para el año 2021 un total de [66.69 millones](https://www.datosmundial.com/america/argentina/telecomunicacion.php) de conecciones.

Es por esto que una nueva empresa (ficticia) especializada en proveer internet con fibra optica desea saber como se encuentra el mercado argentino para su posible entrada.

Para ello se nos encargo hacer un analisis de datos con los datos proporcionados por el gobierno argentino mediante el [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/).

Es por ello  que para el presente proyecto se encontraran 3 archivos:
1. 01 ETL.ipynb
2. 02 EDA-1.ipynb
3. 02 EDA-2.ipynb

A continuacion explicaremos el proceso que se ha seguido

A continuación se explicara como se desarrollo el presente proyecto:

## 1. ETL del dataset

- Para empezar se hizo un proceso de ETL a los archivos proporcionados. En primer lugar se hizo la extraccion de los archivo a traves de la api proporcionada en la pagina web. 
- Una vez obtenida la informacion se hizo la transformacion de los archivos xlsx obtenidos a archivos csv, una vez realizado esto se procede a hacer la carga de los archivos a otro Notebook para su correspondiente EDA
- Para informacion mas detallada tenemos el archivo ***"01 ETL.ipynb"***.

## EDA del dataset   

- Para este paso tenemos 2 archivos principales.
- El primer archivo ***"02 EDA-1.ipynb"*** es donde se realizo la inspeccion inicial de cada archivo para verificar el estado en el que se encuentra. Se busco datos nulos, duplicados, columnas con formato equivocado, etc. En este punto tambien se cambio el nombre de los archivos a uno mas acertado que refleje su contenido.
- El segundo archivo ***"02 EDA-2.ipynb"*** es donde se realizo la busqueda de outliers principalmente, y se busco en general ver porque se dieron y como afectaban a toda la informacion final en general para ver si debian ser tratados o no. Tambien se hizo una union final entre archivos del mismo nivel geopolitico y tambien se descartaron archivos por contener informacion redundante. Al final quedaron 2 archivos que sera analizados en Power BI

## Analisis  

Empezaremos con una descripcion concisa del mercado Argentino con respecto a las telecomunicaciones y mas en especifico con el tema del internet fijo.

Luego empezaremos con la descripcion del internet fijo a nivel nacional en argentina. Para empezar se observara el incremento de accesos en los ultimos años y se compara con el crecimiento fijo aproximado que hay del 1%.

Luego veremos las tecnologias correspondientes que predominan mas las cuales son cablemodem y fibra optica, teniendo esta ultima un incremento considerable en los ultimos años y proyectandose a tener una predominancia en el mercado.

Luego pasaremos al analisis provincial en donde veremos que las provincias centro-orientales de argentina son aquellas que han presentado mayor demanda de este servicio. Se procedera a ver cuales son las provincias con las cuales se puede empezar a introducirse para competir en este mercado.

Por ultimo se daran algunas recomendaciones y se dara por concluido el analisis. 

El mercado argentino esta proyectandose como un buen lugar en donde ofrecer servicios de internet con fibra optica, no obstante es mejor empezar con ciertas provincias centro-orientales, y observar como esta la demanda en el resto del pais a lo largo del tiempo.


<div style="text-align: right;">
  
Contacto:  
Erwin Alain Felix Tayro Mosqueira  
erwin.aftm@gmail.com
</div>