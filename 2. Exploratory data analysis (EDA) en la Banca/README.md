# **Analisis Exploratorio de Datos (EDA) con Pandas en el sector de la BANCA**

- El propósito de este Notebook, es dominar el Analisis Exploratorio de Datos (E.D.A.) en el sector de la Banca con la Libreria de Pandas.

- Para completar el notebook debemos completar los siguientes Objetivos:

---

## OBJETIVOS:

1.  Explorar un Dataset Bancarios con a libreria Pandas.
2.  Constuir tablas dinámicas.
3.  Visualizar el Dataset con varios tipos de gráficos.

---

## ESQUEMA:

*   Materiales y métodos
*   Parte General
    *   Importar librerias
    *   Exploración del Dataset
    *   Tablas dinámicas
    *   Visualización en Pandas
*   Tareas

---

## Materiales y Método

Los datos que utilizaremos son un subconjunto de un Dataset de Marketing Bancario de código abierto del Repositorio:
https://archive.ics.uci.edu/ml/citation_policy.html.

> Este Dataset está disponible públicamente para la investigación. Los detalles se describen en \[Moro et al., 2014].
> Se incluye la siguiente cita de los autores del Dataset:
> \[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014

Durante el trabajo se resuelve la tarea de análisis preliminar de una respuesta positiva (depósito a plazo) a llamadas directas de un banco. en esencia, la tarea es una cuestión de scoring bancario, es decir, de acuerdo con las caracteristicas de un cliente (cliente potencial) se predice su comportamiento (incumplimiento del préstamo, deseo de realizar un depósito, etc.).

En este notebook, intentaremos dar respuesta a un conjunto de preguntas que pueden ser relevantes a la hora de analizar datos Bancarios:

1.  ¿Cuál es la proporción de clientes atraídos por nuestra fuente de datos?
2.  ¿Cuáles son los valores medios de las características numéricas entre los clientes atraídos?
3.  ¿Cuál es la duración media de las llamadas para los clientes atraídos?
4.  ¿Cuál es la edad promedio entre los clientes atraídos y solteros?
5.  ¿Cuál es la edad promedio y la duración de la llamada para los diferentes tipos de atención al cliente?

Además, realizaremos un análisis visual con el fin de planificar las campañas de banca de marketing de forma más eficaz.

- Pandas es una biblioteca de Python que proporciona amplios medios para el análisis de datos. Es usual que los Ingenieros en Machine Learning trabajen con datos almacenados en formatos de tabla como .csv, .tsv o .xlsx. Pandas hace que sea muy conveniente cargar, procesar y analizar dichos datos tabulares mediante consultas similares a SQL. Junto con Matplotlib y Seaborn, Pandas ofrece una amplia gama de oportunidades para el análisis visual de datos tabulares. 
