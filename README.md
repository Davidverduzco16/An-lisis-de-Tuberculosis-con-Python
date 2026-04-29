# Analisis de Tuberculosis con Python
## Proyecto de análisis de datos sobre tuberculosis utilizando Python

Este proyecto consiste en el análisis de datos sobre la tuberculosis (TB) utilizando Python, con el objetivo de limpiar, transformar y visualizar información para comprender mejor el comportamiento de esta enfermedad a nivel mundial.

**Descripción del proyecto**

Se trabajó con datos de casos de tuberculosis y población para analizar la incidencia de la enfermedad por país y año. El estudio permitió identificar patrones importantes relacionados con género, grupo de edad y métodos de diagnóstico, además de observar la evolución de la enfermedad a lo largo del tiempo .

**Aspectos analizados en este trabajo**

Casos de tuberculosis por país y año, distribución por género, Método de diagnóstico, Grupo de edad, Tasa de incidencia por cada 100,000 habitantes. 

**Fuentes de datos: **

who.csv: Datos de casos de tuberculosis y population.csv: Datos de población por país y año,

**Tecnologias que se utilizaron:** 

Python, Pandas, NumPy y Google Colab

**Procesamiento de datos**

Durante el desarrollo del proyecto se realizaron varias etapas importantes:

**Limpieza de datos**

Se identificaron valores faltantes y errores de lectura, como el caso de Namibia donde “NA” era interpretado como valor nulo. También se reemplazaron valores faltantes por 0 para mantener la consistencia de los datos .

**Transformación de datos**

Se utilizó la función melt() para convertir columnas en filas y facilitar el análisis. Además, se crearon nuevas variables como:

Género (Masculino / Femenino)

Método de diagnóstico

Grupo de edad

Casos registrados

Integración de datos

Se realizó la unión entre la base de tuberculosis y la base de población mediante merge(), permitiendo calcular indicadores más completos como la tasa de incidencia.

**Resultados**

El análisis permitió identificar tendencias globales de la tuberculosis, comparar la incidencia entre años y conocer los grupos más afectados, facilitando una mejor comprensión del impacto de esta enfermedad.

Elaborado por: Héctor David Partida Verduzco
