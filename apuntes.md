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
# Estadística básica

# Procesamiento de datos

# Operaciones de datos

# Procesamiento de series de tiempo

# Caso de estudio completo de análisis exploratorio de datos
