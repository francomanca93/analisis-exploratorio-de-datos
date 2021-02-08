<div align="center">
    <h1>Análisis Exploratorio de Datos</h1>
    <img src="https://imgur.com/m4KWSIa.png" width="">
</div>

## Tabla de contenido

- [Introducción al análisis exploratorio de datos](#introducción-al-análisis-exploratorio-de-datos)
  - [Qué es el análisis exploratorio de datos](#qué-es-el-análisis-exploratorio-de-datos)
    - [¿Qué es un EDA?](#qué-es-un-eda)
    - [Historia](#historia)
    - [Etapas del EDA](#etapas-del-eda)
  - [Comparación: EDA vs análisis clásico vs análisis bayesiano](#comparación-eda-vs-análisis-clásico-vs-análisis-bayesiano)
  - [Herramientas de software para análisis exploratorio de datos](#herramientas-de-software-para-análisis-exploratorio-de-datos)
  - [Visualizaciones de EDA](#visualizaciones-de-eda)
- [Estadística básica](#estadística-básica)
- [Procesamiento de datos](#procesamiento-de-datos)
- [Operaciones de datos](#operaciones-de-datos)
- [Procesamiento de series de tiempo](#procesamiento-de-series-de-tiempo)
- [Caso de estudio completo de análisis exploratorio de datos](#caso-de-estudio-completo-de-análisis-exploratorio-de-datos)

# Introducción al análisis exploratorio de datos

## Qué es el análisis exploratorio de datos

### ¿Qué es un EDA?

Significa **Exploratory data analysis**. Aquí comienza todo, antes de crear un modelo debemos saber para que lo vamos a hacer, debemos de tener contexto y la forma de hacerlo es exportando nuestros datos.

### Historia

En los años 90’s se comienza a sonar el termino de **minería de datos** donde se especifica que busca patrones, busca las tendencias más grandes y es justo la minería de datos es lo que le comienza a dar orden a cómo podemos explorar datos y a buscar estos patrones. Esto no es un termino que haya surgido actualmente, de hecho la IA, las primeras redes neuronales salen en los años 70, solo que actualmente ya tenemos el computo necesario para que tu lo puedas hacer de tu computadora, lo que antes solo se podía hacer en el mundo académico y era exclusivo de super maquinas.

Pero, todo esto, ¿de donde viene?

Justo en los años 90’s con la minería de datos se comienzan a crear metodologías, como estas:

- **KDD**: Knowledge discovery in DataBases.
- **SEMMA**: Sample, Explore, Modify, Model, and Assess.
- **CRISP-DM**: Cross Industry Standard Process for Data Mining.

![CRISP-DM](https://imgur.com/xJTgpHU.png)

Y de estás metodologías de minería de datos sale nuestro EDA.

Todo esto surge a partir de una necesidad y nos comenzamos a hacer mucha preguntas, pero la pregunta final es: **¿Puedo contestar o no el requerimiento que me dieron con todos estos datos?** Y si no tenemos los suficientes datos para resolver esta pregunta, eso es lo que hace precisamente el EDA, explicarnos si podemos contestar esta pregunta y si tenemos todo lo necesario para dar una respuesta.

¿Pero qué debemos de hacer si no podemos dar una respuesta? Tenemos que dar un paso atrás, debemos de pedir más datos.
Antes de hacer cualquier modelo de ML o DP debemos de entender:

- **De donde vienen los datos**.
- **El contexto de los datos**.
- **Por qué haremos el modelo**.

### Etapas del EDA

- **Etapa 1**: Definición del problema.
- **Etapa 2**: Preparación de datos.
- **Etapa 3**: Análisis de datos.
- **Etapa 4**: Desarrollo y representación de resultados.

> Nota: Si está en nuestra posibilidad usar toda la base de datos para entrenar nuestro modelo, hay que hacerlo. es mucho mejor pagar un poco para dar una propuesta de valor.

![etapas-eda](https://imgur.com/2KLHcYT.png)

El foco principal del EDA es contar una historia prediciendo cuánto se va optimizar el problema implementando el modelo que vamos a proponer. Un científico de datos le da un valor a los datos.

## Comparación: EDA vs análisis clásico vs análisis bayesiano

¿Cuáles son las características entre **EDA**, **análisis clásico/estadístico** y **análisis bayesiano**?

![eda-vs-ac-ab](https://imgur.com/g5gjzJT.png)

- **Análisis clásico**: Aquí simplemente mostramos los resultados, no importa que pase con esa información, no importa que es lo que significa o que hubo antes como tal, solo se presenta un análisis clásico, un análisis de medias, un análisis estadístico, pero no se da un contexto de un problema que vayamos a resolver.

- **Análisis bayesiano**: Siempre considera que es la distribución a priori, es decir que es lo que paso anteriormente para yo predecir el futuro, pero aveces no toma en consideración que es lo que puede pasar con este modelo, que mas podemos entender y que otro tipo de variables podemos meter.

- **EDA**: Este es totalmente dinámico, puede regresar para entender lo que está pasando y al final lanzar un modelo de **ML, DP**, alguna **automatización** o alguna **mejora para el negocio** que le dé una ganancia, por eso es muy importante para entender que el EDA, parte del contexto del negocio, parte de una serie de hipótesis para hacer un análisis dinámico para entender que valor y que propuesta voy a dar.

> En el data analysis clasico y bayesiano, el modelo va antes del data analysis, en cambio en el análisis exploratorio (EDA), primero se analizan los datos para proponer un modelo.

![comparativas](https://imgur.com/hi8N3va.png)

[Hands-On Exploratory Data Analysis with Python](https://www.amazon.es/Hands-Exploratory-Data-Analysis-Python/dp/1789537258)

[Hands-On Exploratory Data Analysis with Python in Github](https://github.com/PacktPublishing/Hands-on-Exploratory-Data-Analysis-with-Python)

## Herramientas de software para análisis exploratorio de datos

- **Python-Jupyter**: Se especializa en juntar texto con código y es el favorita de los científicos de datos.
- **AWS SAGEMAKER**: Está diseñada para el deploy de los modelos de Machine Learning. También tiene notebooks y este se utiliza más para probar modelos con bastante poder de computo, porque cobra a partir del tiempo que se emplea. Otra ventaja que tiene es que podemos llevar todo lo que hagamos a deploy como modelo de producción, osea, a que se haga una API.
- **AWS EMR**: EMR es casi lo mismo que Spark, ya que están diseñados para procesamiento de datos a grandes volúmenes tenido como base Hadoop. Es muy empleado para Data Engineer como preprocesamiento antes de un modelo o para modelos que requieren procesamiento en tiempo real. Si es que queremos que nuestro modelo sea en tiempo real, debemos de hablar con el Data Engineer para desde un inicio pedir este requerimiento.
- **Google Jupyter Notebook Cloud**: Es la forma de llevar nuestros notebooks a producción.
- **Azure Notebooks**: Azure apuesta que aquí solo se haga experimentación y que el deploy del modelo se haga en su plataforma.
- **R Studio**: Este entorno tiene el Kernel de R y es un software especializado en estadística. Tiene muchas más bibliotecas de estadística que en el caso de Python, apenas están llegando.
- **Knime**: Esta herramienta se enfoca para personas que no saben programar, es para personas que tiene conocimiento de negocio y no hay un experto que haga el flujo de trabajo del área de datos.

## Visualizaciones de EDA

¿Por qué es importante hacer una buena visuzalización de datos?

La visualización de datos no es sólo una herramienta útil para presentar resultados sino también para la exploración eficaz de los mismos, la visualización de datos efectiva es una habilidad técnica cada día más codiciada, porque los gráficos bien diseñados son capaces de transferir una gran cantidad de información en poco tiempo.

[Jupyter de la clase - Visualizacion de datos](1.introduccion-analisis-exploratorio-de-datos/visualizacion-de-datos.ipynb)

[Jupyter con ejemplos de diversas visualizaciones de datos](1.introduccion-analisis-exploratorio-de-datos/visualizaciones-de-datos-en-colab.ipynb)

# Estadística básica

# Procesamiento de datos

# Operaciones de datos

# Procesamiento de series de tiempo

# Caso de estudio completo de análisis exploratorio de datos
