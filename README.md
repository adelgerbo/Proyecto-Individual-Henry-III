<h1 align=center> HENRY’S LABS </h1>

<h2 align=center>PROYECTO INDIVIDUAL III -- DATA ANALYTICS<br>
    Alejandro del Gerbo Actis</h2>


## **Temática**

El proyecto propuesto puede verse en su totalidad en el [siguiente link](https://github.com/adelgerbo/Proyecto-Individual-Henry-III/blob/main/CONSIGNAS.md).

Como resumen, se nos entregaron 4 datasets de 3 empresas dedicadas a brindar cursos online.

Debiamos comenzar haciendo un Analisis Exploratorio de los Datos [(EDA)](https://www.ibm.com/ar-es/cloud/learn/exploratory-data-analysis), realizando luego las transformaciones que consideraramos necesarias, para realizar luego un análisis de los datos y realizar una presentación al respecto.

## **Librerias utilizadas**
* [Pandas](https://pandas.pydata.org/) y [Numpy](https://numpy.org/) para la exploración, transformación y manipulación de los datos
* [Seaborn](https://seaborn.pydata.org/) y [Matplotlib](https://matplotlib.org/) para las visualizaciones
* [Wordcloud](https://pypi.org/project/wordcloud/) para la generación de [Nubes de Palabras](https://www.questionpro.com/blog/es/nubes-de-palabras/)
* [NLTK Stopwords](https://www.nltk.org/index.html) para la limpieza de textos


## **EDA (Analisis exploratorio de datos)**
Cada dataset contenia diferentes características, por lo que los analizamos por separado.

### **Udemy**
Este dataset no contenia nulos y solo 6 registros duplicados, que eliminamos.

Udemy ofrece cursos gratuitos y pagos, y verificamos que el 90% de los cursos son pagos.

Con respecto al precio, notamos que la mayor parte se encuentra en el rango de hasta 60 dolares, con muy poca cantidad de cursos en el rango medio de precio, pero con una cantidad considerable de cursos en el mayor valor de 200 dólares.

Verificamos tambien que la mayor parte de los cursos son para todos los niveles y para principiante, con menos cantidad de cursos para nivel intermedio y aun menos para expertos.

Con respecto a la temática, brinda mayor cantidad de cursos de Desarrollo Web y de Finanzas de los Negocios.

Por último, generamos una Wordcloud con la descripción de los cursos ofrecidos.

<img src="udemy.png" alt="drawing" width="800"/>

### **EDX**
Este dataset contenía 120 nulos en la columna de Enrolados. Esta columna era de vital importancia para el análisis, ya que la misión principal que nos asignaron consistía en evaluar la contratación de cursos en función de las otras variables, por lo que decidimos eliminar solo los registros con nulos.

EDX dispone de cursos en los cuales los estudiantes manejan sus tiempos y otros que son llevados adelante por instructores y que respetan un cronograma. Detectamos que solo el 5% de los cursos son conducidos por instructores.

Al igual que Udemy, EDX ofrece la mayor cantidad de cursos en nivel Principiante y la menor cantidad en nivel Avanzado.

Los temas mas populares de sus cursos son Computer Science y Business & Managment.

En cuanto al idioma, la gran mayoría de los cursos son en inglés, con los cursos en español en segundo lugar pero con una cantidad muy menor y el resto de los idiomas ofrecidos, en muy poca cantidad de cursos disponibles.

Por último, generamos una Wordcloud con la descripción de los cursos ofrecidos.

<img src="EDX.png" alt="drawing" width="800"/>

Debido a la preponderancia del idioma inglés en los cursos, generamos una segunda Wordcloud solo en español.

<img src="EDX2.png" alt="drawing" width="800"/>

### **COURSERA**
En este caso teniamos a disposición dos datasets, uno con información acerca de los cursos y la institución que los dicta, y otro con reviews de estudiantes.

El dataset con las reseñas incluía dos tercios de registros duplicados, los cuales eliminamos para no distorsionar el análisis.

Analizamos las reseñas y notamos que son en su mayoría positivas, con una cantidad ínfima de malos comentarios.

Generamos una Wordcloud con las reseñas y notamos que las palabras más utilizadas se expresan en el mismo sentido.

<img src="reviews.png" alt="drawing" width="800"/>

Por último, generamos un Wordcloud con los nombres de los cursos

<img src="coursera.png" alt="drawing" width="800"/>

## **Power BI**
La parte final del trabajo la realizamos en Power BI, donde mediantes diversas visualizaciones exponemos todos los datos contenidos en los datasets, relacionandolos entre ellos.

Por últimos, incluimos un KPI para presentar a la nueva empresa, que consiste en obtener como meta un promedio de puntaje en las reviews superior a 4.75.

## **Código y Archivos**
Pueden encontrar en mi repositorio de Github el [Notebook con el EDA](https://github.com/adelgerbo/Proyecto-Individual-Henry-III/blob/main/EDA.ipynb) y [las visualizaciones en Power BI](https://github.com/adelgerbo/Proyecto-Individual-Henry-III/blob/main/udemy.pbix)

## **Datos sobre el autor**

**Alejandro del Gerbo Actis**

adelgerbo@gmail.com
