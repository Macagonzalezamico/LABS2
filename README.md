<p align="center">
  <img src="image/README/1686531329752.png">
</p>

<h1 align="center">PROYECTO INDIVIDUAL Nº2</h1>

<h2 align="center">MOOCs</h2>

### Descripción del problema (Contexto y rol a desarrollar)

#### Contexto

Los MOOCs (cursos masivos abiertos y en línea, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, ofreciendo acceso a contenido de calidad y práctico desde la comodidad del hogar. En este contexto, muchas plataformas ofrecen cursos gratuitos y pagos, compitiendo por captar y retener a la mayor cantidad de clientes.

En este proyecto, nos encontramos trabajando para una startup de tecnología que desea ingresar al mercado de los cursos en línea. Para tomar decisiones estratégicas, la empresa ha adquirido conjuntos de datos de posibles competidores y nos ha asignado el rol de analizar y sacar conclusiones a partir de estos datos.

Vamos a trabajar con 4 csv: `'Coursera_courses.csv', 'Coursera_reviews.csv', 'edx_courses.csv' y 'udemy_courses.csv'.`

Links del proyecto:

GITHUB: [Macagonzalezamico/LABS2 (github.com)](https://github.com/Macagonzalezamico/LABS2)

#### Rol a desarrollar

Nuestro rol consiste en realizar un análisis de los datos de los cursos en línea para segmentar el nivel de ventas según el precio, idioma, nivel y rating de cada curso. El objetivo es analizar cómo influyen estas variables en la demanda del producto vendido.

### Propuesta de trabajo (indicaciones)

* El primer paso consistirá en realizar un merge de los conjuntos de datos de Coursera para poder trabajar con los datos juntos. Esto nos permitirá tener una visión completa de los cursos y sus características.
* Hice la limpieza pertinente de las columnas que no voy a utilizar.
* Elimine los registros duplicados.
* Realice cambio de Nombres de las columnas.
* Hice Analisis se Columnas.
* Hice distintos graficos como los de Barra, Tortas, Dispersion, Linea de tiempo, Cajas, Histogramas entre otras.
* Realice Analisis de Variables Numericas, de Variables Categoricas, de Relación, de Cantidad, de dificultad, de Tiempo.
* Converti las columnas en formato Fecha.
* Hice conteos de los valores unicos.
* Cree una nube de palabras (Word Cloud) de los Titulos mas repetidos.

### `EDA (Exploratory Data Analysis)`

Realizaremos un análisis exploratorio de los datos en un notebook. Documentaremos cada paso con claridad, incluyendo conclusiones en cada gráfico utilizado y análisis de las observaciones realizadas. Utilizaremos celdas Markdown para explicar nuestro trabajo.

En caso de utilizar librerías como pandas_profiling, acompañaremos los gráficos con análisis propios.

#### `Dashboard`

Crearemos un dashboard funcional y coherente con el storytelling. El dashboard incluirá filtros interactivos que permitan explorar los datos en detalle. La presentación de los datos será clara, y utilizaremos un diseño que facilite la interpretación y el análisis de la información. La elección de los gráficos será coherente con las variables a visualizar. La estética y el diseño serán elementos importantes a considerar.

### `KPIs`

Realizare 3 KPIs y los mostrare y explicare en el dashboard.

### `Repositorio de GitHub`

El repositorio va a contener el **Readme.**

### Reporte de Analisis

En el análisis de los archivos CSV de Coursera y Udemy, se realizaron diversas exploraciones y visualizaciones para comprender mejor los datos. En el caso de Coursera, se identificó el curso más popular, se contaron las inscripciones por institución y se examinaron las calificaciones y fechas de las reseñas. También se generó una nube de palabras con los títulos de los cursos. En el caso de Udemy, se analizaron los títulos de los cursos, la distribución entre cursos gratuitos y de pago, los precios, las inscripciones y el nivel de dificultad. Se realizaron visualizaciones como gráficos de torta, histogramas, gráficos de dispersión y gráficos de líneas.

Conclusiones:

1. El curso más popular en Coursera es "Programación para todos (Introducción a Python)" con 45,218 inscritos.
2. La Universidad de Michigan es la institución con más inscritos en Coursera, seguida de cerca por otras universidades.
3. Se encontraron 1,453,954 valores duplicados en la columna 'course_id' de Coursera.
4. Los cursos con una calificación de 5 tienen la calificación más alta, y el curso "IA para todos" fue considerado muy interesante por los inscritos.
5. Los títulos de los cursos más comunes en Udemy incluyen "Crear una tarjeta de felicitación animada a través de Google Slides" y "Clases de guitarra acústica de blues".
6. La mayoría de los cursos populares en Udemy son de pago.
7. El nivel de dificultad "Principiante" tiene la mayor cantidad de suscriptores en Udemy.
8. La distribución de precios en Udemy muestra una concentración de cursos gratuitos y precios bajos.
9. La cantidad de inscritos en los cursos aumentó en mayo de 2012 en Udemy.
10. Las palabras más destacadas en los títulos de los cursos son "Beginner", "Learn" y "Course".
