 # Solución al problema de Desercion Laboral en Empresa

## Análisis de Negocio:
Identifiqué un caso preocupante de rotación de empleados, sin tener una visión clara de las implicaciones que esto conlleva dentro de la empresa. Por lo que  consideré como objetivo principal analizar a fondo las causas y consecuencias de la deserción laboral, así como identificar patrones y tendencias que puedan estar contribuyendo a este fenómeno. 

En primer lugar, se llevaré a cabo un análisis que permita entender cuantitativamente los gastos que ocasiona la rotación de empleados, incluyendo los costos asociados a la búsqueda, selección y capacitación de nuevos empleados y el impacto que representa para la empresa.

Una parte esencial será encontrar una métrica adecuada para medir el abandono laboral en la empresa. Esto permitirá tener una visión clara y precisa del problema, facilitando la toma de decisiones y estrategias para su mitigación.

Asimismo, estableceré que porcentaje de empleados se encuentra actualmente en riesgo de abandonar sus puestos de trabajo para visualizar el riesgo por el que pasa la empresa.

Por último, se determinaré los perfiles de los empleados más propensos al abandono laboral. Para ello, realizaré un análisis detallado de variables dentro del conjunto de datos y otros factores que puedan influir en la decisión de dejar la empresa. Esto con la finalidad de dirigiir esfuerzos y recursos hacia acciones que resulten en la retención del talento humano.

En conclusión, en el presente proyecto busco implementar un sistema integral que permita reducir la rotación de empleados en la empresa, abordando tanto las causas subyacentes del problema como los aspectos individuales que pueden influir en la decisión de abandonar el trabajo. Mediante un enfoque cuantitativo y un análisis profundo, se aspira a mejorar la retención del talento humano, fomentando un ambiente laboral estable, productivo y satisfactorio para todos los miembros de la organización.

## Fuente de datos

La información oficial provista por el Hackathon HackerHEarth 2020. Archivo de información: Employees.csv

## Métodos
- Análisis De Negocio
- ETL 
- Análisis Exploratorio De Datos
- Análisis de penetración
- Generación De Insights
- Tabla de reporteo

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
- [Notebook](https://colab.research.google.com/drive/1GAj6cuPgsOT-7OtdXyYUK9M_P1rYYlVg?usp=sharing)

- [Dashboard](https://public.tableau.com/views/Dashboard-Desercinlaboral/Dashboard1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

## Análisis

La tasa de abandono laboral dentro de la empresa del año pasado fue de un **39.7%**, lo que equivalió a una pérdida total de **$2,719,005.9** dólares. Fidelizar a los empleados podría reducir este problema y ahorrar dinero. A continuación, se presentan tres posibles escenarios:

1. Reducir un **10%** la tasa de abandono nos permitiría ahorrar **$271,900** dólares al año.
2. Reducir un **20%** la tasa de abandono nos permitiría ahorrar **$543,801** dólares al año.
3. Reducir un **30%** la tasa de abandono nos permitiría ahorrar **$815,701** dólares al año.

Para este año se pronostican las mismas cifras, se compara la tasa de abandono actual de 16.12% y se toma en consideración que el año aún no ha concluido, se espera un aumento del 23.58%. Esto equivale a que 19 empleados dejarán la empresa este año. Con estos datos surge la siguiente pregunta: ¿cuántos empleados podríamos retener y cuánto dinero representaría esa retención?. Considerando estos tres escenarios, obtendríamos lo siguiente:

1. Con el **10%** de retención, mantendríamos a **1** empleado de ventas y ahorraríamos **$12,482.41** dólares.
2. Con el **20%** de retención, mantendríamos a **3** empleados de ventas y ahorraríamos **$24,964.82** dólares.
3. Con el **30%** de retención, mantendríamos a **5** empleados de ventas y ahorraríamos **$37,447.22** dólares.

Considerando los datos anteriores, se puede establecer un gasto máximo de **$37,447** dólares para acciones específicas orientadas a la retención del personal, lo cual estaría justificado ya que esta cantidad es igual al pronóstico de pérdida para este año.

Los empleados que abandonan la empresa en su mayoría proviene del personal de ventas, especialmente de aquellos con un bajo nivel educativo (Primaria), estado civil soltero, alta carga de trabajo y bajos salarios. Invertir en estrategias para retener al personal resultará en un ahorro significativo y un ambiente laboral más estable y productivo.



## Solución

Con la ayuda del Machine Learning se creara un sistema integral que ayudara a proporcionó información valiosa sobre los empleados que podrian estar en riesgo de dejar la empresa en un futuro cercano y así  desarrollar iniciativas personalizadas para involucrar y motivar a estos empleados, abordando las preocupaciones que puedan estar afectando su satisfacción laboral.


## Vistaso rápido a los resultados

> Árbol de decisiones

![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Arbol%20de%20perfil%20de%20empleado.png)

Nota: El árbol de decisiones señala que los empleados con mayor probabilidad a abandonar la empresa son: aquellas personas que hacen horas extras, con posiciones bajas dentro de la empresa, son solteros y la distacia del trabajo a su casa es mas de 6 kilometros

> Riesgo de abandono por puesto
![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Riesgo_abandono_por_puesto.png)

Nota: Los puestos con más riesgo de abandono laboral son "Sales Representative"


> Riesgo de abandono por edad 
![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Riesgo_abandono_por_edad.png)

Nota: Las personas que más desercionan son personas entre los 20 a 22 años.

