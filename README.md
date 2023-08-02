# Solución al problema de Desercion Laboral

## Análisis de Negocio:
Se identificó un caso preocupante de rotación de empleados, sin tener una visión clara de las implicaciones que esto conlleva dentro de la organización. Por lo que se a considerado como objetivo principal analizar a fondo las causas y consecuencias de la deserción laboral en la empresa, así como identificar patrones y tendencias que puedan estar contribuyendo a este fenómeno. 

En primer lugar, se llevará a cabo un análisis que permita entender cuantitativamente los gastos que ocasiona la rotación de empleados, incluyendo los costos asociados a la búsqueda, selección y capacitación de nuevos empleados y el impacto que representa para la empresa.

Una parte esencial será encontrar una métrica adecuada para medir el abandono laboral en la empresa. Esto permitirá tener una visión clara y precisa del problema, facilitando la toma de decisiones y estrategias para su mitigación.

Asimismo, se determinara que porcentaje de empleados se encuantra actualmente en riesgo de abandonar sus puestos de trabajo para visualizar el riesgo por el que pasa la empresa.

Por último, se enfocará en la identificación de los perfiles de empleados más propensos al abandono laboral. Para ello, se realizará un análisis detallado de variables dentro del conjunto de datos y otros factores que puedan influir en la decisión de dejar la organización. Esto con la finalizad de dirigiir esfuerzos y recursos hacia acciones que resulten en la retención del talento humano.

En conclusión, el presente proyecto busca implementar un sistema integral que permita reducir la rotación de empleados en la empresa, abordando tanto las causas subyacentes del problema como los aspectos individuales que pueden influir en la decisión de abandonar el trabajo. Mediante un enfoque cuantitativo y un análisis profundo, se aspira a mejorar la retención del talento humano, fomentando un ambiente laboral estable, productivo y satisfactorio para todos los miembros de la organización.

## Fuente de datos

La información oficial provista por el Hackathon HackerHEarth 2020. Archivo de información: Employees.csv

## Métodos
- Análisis De Negocio
- Análisis Exploratorio De Datos
- Análisis de penetración
- Generación De Insights

## Tech Stack
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau
- GitHub

## Explora
[Notebook](https://colab.research.google.com/drive/1GAj6cuPgsOT-7OtdXyYUK9M_P1rYYlVg?usp=sharing)

[Dashboard](https://public.tableau.com/views/Dashboard-Desercinlaboral/Dashboard1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

## Análisis
La tasa de abandono lavoral dentro de la empresa es del 16.12%, y se ha observado que en su mayoría proviene del personal de ventas, especialmente de aquellos con un bajo nivel educativo (Primaria), estado civil soltero, alta carga de trabajo y bajos salarios. Este problema ha resultado en una pérdida de **$2,719,005.912** en el último año.

Es evidente que fidelizar a los empleados podría reducir este problema y hacernos ahorrar dinero. A continuación, se presentan tres escenarios para considerar:

1. Reducir un **10%** la tasa de abandono nos permitiría ahorrar **$271,900** cada año.
2. Reducir un **20%** la tasa de abandono nos permitiría ahorrar **$543,801** cada año.
3. Reducir un **30%** la tasa de abandono nos permitiría ahorrar **$815,701** cada año.

Comparando con la tasa de abandono del año anterior del 39.7%, vemos que en el año actual todavía tenemos un faltante del 23.58%. Se estima que 19 empleados dejarán la empresa este año, surge la pregunta de ¿cuántos empleados podríamos retener y cuánto dinero representaría esa retención?. Considerando estos tres escenarios, obtendríamos lo siguiente:

1. Con el **10%** de retención, mantendríamos a **1** empleado de ventas y ahorraríamos **$12,482.41**.
2. Con el **20%** de retención, mantendríamos a **3** empleados de ventas y ahorraríamos **$24,964.82**.
3. Con el **30%** de retención, mantendríamos a **5** empleados de ventas y ahorraríamos **$37,447.22**.

Tomando en cuenta los datos anteriores, se puede establecer un gasto máximo de **$37,447** para acciones específicas orientadas a la retención del personal de ventas, lo cual estaría justificado ya que esta cantidad es igual al pronóstico de pérdida para este año. Invertir en estrategias para retener al personal resultará en un ahorro significativo y un ambiente laboral más estable y productivo.


## Vistaso rápido a los resultados

[![](https://pandao.github.io/editor.md/examples/images/4.jpg](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Arbol%20de%20perfil%20de%20empleado.png)]

## Solución
Se crea un modelo de Machine learning para poder predecir a los empleados con más probabilidad de dejar la organización





