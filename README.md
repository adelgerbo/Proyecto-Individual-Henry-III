<h1 align=center> HENRY’S LABS </h1>

<h2 align=center>PROYECTO INDIVIDUAL III -- DATA ANALYTICS<br>
    Alejandro del Gerbo Actis</h2>


## **Temática**

El proyecto propuesto puede verse en su totalidad en el [siguiente link](https://github.com/adelgerbo/Proyecto-Individual-Henry-III/blob/main/CONSIGNAS.md).

Como resumen, se nos entregaron 4 datasets de 3 empresas dedicadas a brindar cursos online.

Debiamos comenzar haciendo un Analisis Exploratorio de los Datos [(EDA)](https://www.ibm.com/ar-es/cloud/learn/exploratory-data-analysis), realizando luego las transformaciones que consideraramos necesarias, para realizar luego un análisis de los datos y realizar una presentación al respecto.

## Librerias utilizadas
* [Pandas](https://pandas.pydata.org/) y [Numpy](https://numpy.org/) para la exploración, transformación y manipulación de los datos
* [Seaborn](https://seaborn.pydata.org/) y [Matplotlib](https://matplotlib.org/) para las visualizaciones
* [Wordcloud](https://pypi.org/project/wordcloud/) para la generación de [Nubes de Palabras](https://www.questionpro.com/blog/es/nubes-de-palabras/)
* [NLTK Stopwords](https://www.nltk.org/index.html) para la limpieza de textos


## EDA (Analisis exploratorio de datos)
Cada dataset contenia diferentes características, por lo que los analizamos por separado.

### Udemy
Este dataset no contenia nulos y solo 6 registros duplicados, que eliminamos.
Udemy ofrece cursos gratuitos y pagos, y verificamos que el 90% de los cursos son pagos.
Con respecto al precio, notamos que la mayor parte se encuentra en el rango de hasta 60 dolares, con muy poca cantidad de cursos en el rango medio de precio, pero con una cantidad considerable de cursos en el mayor valor de 200 dólares.
Verificamos tambien que la mayor parte de los cursos son para todos los niveles y para principiante, con menos cantidad de cursos para nivel intermedio y aun menos para expertos.




## Código y Archivos
Pueden encontrar en mi repositorio de Github el [Notebook con el EDA y los modelos supervisados](https://github.com/adelgerbo/Proyecto-Individual-Henry-II/blob/main/EDA%20y%20entrenamiento%20supervisado.ipynb), el [Notebook con los modelos no supervisados](https://github.com/adelgerbo/Proyecto-Individual-Henry-II/blob/main/No%20Supervisado.ipynb) y la [Carpeta que contiene los archivos csv con las predicciones enviadas a Henry](https://github.com/adelgerbo/Proyecto-Individual-Henry-II/tree/main/Predicciones%20enviadas)


## **Datos sobre el autor**

**Alejandro del Gerbo Actis**

adelgerbo@gmail.com
