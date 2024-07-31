<center>
<h1> BD_Customer_Shopping_Trends </h1>
</center>

Este conjunto de datos incluye varias características relacionadas con las preferencias de compra de los clientes, ofreciendo información valiosa sobre el comportamiento y los patrones de compra de los consumidores. 

Las características incluyen la edad del cliente, el género, el monto de la compra, los métodos de pago preferidos, la frecuencia de las compras y las calificaciones de los comentarios. Además, se incluyen datos sobre el tipo de artículos comprados, la frecuencia de compra, las temporadas de compra preferidas y las interacciones con las ofertas promocionales. 

## 🎯Objetivo: 

Comprender las preferencias y tendencias de los clientes es fundamental para que las empresas adapten sus productos, estrategias de marketing y la experiencia general del cliente. 

El análisis de estos datos puede ayudar a las empresas a tomar decisiones informadas, optimizar las ofertas de productos y mejorar la satisfacción del cliente. El conjunto de datos es un recurso valioso para las empresas que buscan alinear sus estrategias con las necesidades y preferencias de los clientes.

Cojunto de Datos descargado de Kaggle, archivo: `shopping_trends_updated.csv`, [Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

## Análisis en Python fundamental para comprender la naturaleza de los datos, detectar posibles errores o inconsistencias, y tomar decisiones informadas en el proceso de análisis y modelado. Al que luego se llevó a cabo un análisis más profundo en Power BI.

Puede visualizar el archivo detallado realizado en Jupyter Notebook [AQUÍ]()
Donde se realizó lo siguiente: 
+ Importar librerías
+ Carga del dataset (nombre del data frame `data`)
+ Análisis de la Calidad de los Datos
    - Cantidad de registros y columnas:
```
data.shape
```
    - Conocer información de los datos (vista previa de los primeros 5 registros):
```
data.head()
```
    - Tipos de datos para cada columna:
```
print(data.dtypes)
```
    - Suma de valores nulos por columna:
```
print(data.isna().sum()
```
    - Verificar si hay duplicados:
```
print(data.duplicated().sum())
```
sf


