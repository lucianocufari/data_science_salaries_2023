# Data Science Salaries 2023

Este repositorio alberga un proyecto dedicado al analisis de un data set del campo de Data Science, para entender la distribución de los salarios y cómo estos pueden variar en función de factores como la ubicación del empleado y del empleador, el nivel de experiencia, el tipo de empleo, entre otros.

Para estar acorde al branding de Upgrade Hub, utilicé un color scale dedicado a su color principal (#D8F64B), variando en tonalidades para mejor comprensión de las gráficas.

A continuación, iré repasando cada punto del índice otorgado en el Jupyter Notebook, para brindar distintas conclusiones derivadas de las gráficas presentadas.


## 1.1.2 Primer Paso

El primer paso fue sencillo, ya que, luego de explorar y comprender el dataset, podemos apreciar que no presenta valores nulos, con lo cual no fue necesario realizar ninguna limpieza ni modificación de las variables.

Dividí las variables en numéricas y categóricas, para comprender cuales hay que trabajar de una manera en particular, teniendo en cuenta las diferencias que presenta la metodología de cada tipo a la hora de extraer los datos.


## 1.1.3 Segundo Paso

Una vez que hemos limpiado y preparado nuestros datos, estamos listos para comenzar a explorarlos y visualizarlos. Al no tener un objetivo específico para nuestro análisis, comencé a formular preguntas sobre nuestros datos, que guiarán nuestras visualizaciones y análisis, y nos ayudarán a descubrir patrones, tendencias e información valiosa.


### 1.1.3.2 Salario Promedio por Nivel de Experiencia

Podemos ver que, efectivamente, el salario promedio aumenta a la par con el nivel de seniority. Para un Junior, o "Entry Level", el salario promedio es de 70k (siempre en USD). Para un Medior, es de 100k. Para un Senior, 146k. Finalmente, para un Expert, 196k.

Aún así, a partir de Medior podemos encontrar excepciones a la regla de manera bastante recurrente, en las cuales incluso superan la media de un Expert.


### 1.1.3.3 Evolución del Salario Medio a través de los Años

Desde el 2020 que ha ido incrementando el salario medio. Lo mas destacable de esta gráfica, es el aumento exponencial que tuvo en el lapso de un año, desde 2021 hasta 2022.


### 1.1.3.4 Proporción de Trabajo Remoto entre Diferentes Roles de Trabajo

Aquí podemos ver que no existe una lógica marcada para la proporción de trabajo remoto dependiendo del rol. 


### 1.1.3.5 Relación entre el Tamaño de la Empresa y el Salario

Podemos aoreciar que el salario medio es mayor en las empresas medianas, mientras que el menor salario medio se encuentra en las empresas pequeñas. Aún así, el potencial para tener un salario elevado es similar en las empresas medianas y en las empresas grandes.


### 1.1.3.6 El País con Mayor Cantidad de Trabajadores en Remoto

Estados Unidos es, con una diferencia abultadísima, el país con mayor cantidad de trabajadores en remoto. Le sigue, lejos, el Reino Unido y Canadá.


### 1.1.3.7 Cambio de la Proporción de Trabajo Remoto con el Paso de los Años

Esta gráfica nos dice que la tendencia de trabajo remoto comenzó a disminuir levemente desde el 2021. Coincide con el fin de la pandemia a nivel mundial, y puede significar que la intención de las empresas sea volver lentamente a una modalidad similar al período pre-pandemia.


### 1.1.3.8 País con los Salarios Promedio en USD más Altos

Israel es el país con los salarios en dólares mas altos en promedio, con más del doble que el siguiente país, Malaysia.


### 1.1.3.9 Distribución de los Roles de Trabajo en las Diferentes Categorías de Experiencia

En primer lugar, podemos ver que la mayor cantidad de empleados se encuentran con el nivel de Senior. Luego están como Medior, seguido por Junior, y finalmente la menor cantidad esta como Expert.

Luego, vemos que, tanto para las categorías Senior, Medior, y Junior, los roles mas comunes, y prácticamente con la misma proporción, son los siguientes: Data Engineer, Data Scientist, y Data Analyst.

Para la categoría de Expert, en cambio, se puede apreciar que hay una proporción mayor para el rol de Data Engineer.


### 1.1.3.10 Variantes del Salario Promedio en Función del Tipo de Empleo

El salario promedio es mayor en trabajadores con la modalidad Full-Time. 

En segundo lugar se encuentran los que se encuentran con un contrato de "Contractor" or "Contract Labor". Por lo general, se trata de personas contratadas para un proyecto o un periodo de tiempo concretos, en lugar de empleados fijos de la empresa. 

Le siguen los trabajadores que se encuentran como Freelance, y en último lugar, como era de esperarse, los que estan en Part-Time.


### 1.1.3.11 Top 10 de los Empleos mas Demandados

Los tres empleos mas demandados, y por una diferencia bastante grande con el resto, son: Data Engineer, Data Scientist, y Data Analyst.


### 1.1.3.12 Top 10 de los Empleos mas Cotizados

Podemos ver que el salario promedio de los 10 empleos mas cotizados es similar, salvo Data Science Tech Lead, que es el mas cotizado, y que tiene un promedio de salario bastante mas elevado que el resto.


### 1.1.3.13 Top 10 de Empleos con Mayor Proporción de Trabajo Remoto

La proporción de los 10 empleos con mayor promedio de trabajo remoto es bastante dispar. Se pueden ver tres subgrupos. En primer lugar, Applied Data Scientist, Applied Machine Learning Scientist, y AI Scientist. Luego, se encuentra el grupo de Analytics Engineer, 3D computer Vision Researcher, AI Programmer, y Applied Machine Learning Engineer. A partir de allí, el promedio desciende de maner contínua en los últimos tres empleos, que son los que catalogo como el tercer subgrupo.



