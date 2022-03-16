# TRABAJO 1 - UNIDAD 1 INGENIERÍA DE DATOS

### Universidad EAFIT

### Integrantes
* JOSE JORGE MUÑOZ MERCADO
* LINA MARÍA BELTRÁN DURANGO

En este trabajo hemos diseñado e implementado un ecosistema de almacenamiento y
procesamiento de datos a partir de dos bases de datos: CAMBIO CLIMÁTICO o
CALENTAMIENTO GLOBAL con datos de varios países, dataset obtenido de [Kaggle](https://www.kaggle.com/sevgisarac/temperature-change), y una Base
de Datos Relacional con 8 tablas simulando los datos de una empresa ficticia a partir de
código SQL. Para esto se diseñó e implementó un Datalake para almacenar los datos en S3,
se catalogaron (con Glue), se implementaron ETL para cada Base de Datos, se hicieron
consultas con SQL (Athena y Hive), se cargaron datos desde S3 a Jupyter Notebook y se hizo
un Análisis Exploratorio de Datos con Spark (Jupyter/pyspark) para los datos relacionados
con Cambio Climático.

## Notebooks
Análisis exploratorio en PySpark
## datasets
Conjuntos de datos

## Casos de estudio
1. Cambio climático: El sitio web de cambio de temperatura de FAOSTAT difunde
estadísticas del cambio de temperatura superficial promedio por país, con actualizaciones
anuales. La data actual cubre el período entre 1961 y 2019. Los datos se basan en los datos
GISTEMP disponibles públicamente y los datos de cambio de temperatura de la superficie
global distribuidos por el Instituto Goddard de Estudios Espaciales de la Administración
Nacional de Aeronáutica y del Espacio (NASA-GISS).
Esta base de datos está conformada por las siguientes tablas almacenadas en S3 de la zona
Raw:
* Environment_data.csv
* FAOSTAT_2020.csv
* FAOSTAT_2022.csv

2. Empresa ficticia: Esta base de datos fue creada con motor SQL. Se trata de una empresa cualquiera, puede ser
manufacturera o solo de ventas, la cual maneja un catálogo de n cantidad de productos.
Dentro de esta BD se encuentran las siguientes tablas relacionales:

* Productlines, correspondiente a las líneas de productos
* Products, correspondiente a los productos en venta
* Orderdetails correspondiente a los detalles de las ordenes
* Employees la cual detalla la información de los empleados
* Customers correspondiente a la información de los clientes
* Orders correspondiente a la información rasa de las ordenes
* Offices la cual detalla la información de las oficinas
* Payments la cual detalla la información de pago

