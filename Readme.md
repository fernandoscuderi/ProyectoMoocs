# Proyecto Individual 2  - MOOCS 
---

*Repositorio: https://github.com/fernandoscuderi/ProyectoMoocs*

---

**INTRODUCCION:** <br>
Una startup de tecnología está interesada en sumarse al mercado de cursos online, y nos provee datasets de posibles competidores para analizar y sacar conclusiones de los datos recolectados.

Nos solicita analizar el impacto en la demanda de ventas de variables como: Precio, Idioma, Nivel y Rating.
También nos solicita visualizar un KPI provisto por la startup, y establecer otros 3 producto de nuestro analisis y realizar un dashboard para una presentación del mismo.

---

- Inicialmente, de los CSV provistos por la empresa (incluidos en la raiz del repositorio), se procede con el ETL. Dejando limpias las columnas a utilizar, eliminando las que no, y estableciendo los tipos de datos de cada una. <br>
Una vez realizado este paso, se exportan los csv limpios a una carpeta con nombre "dfLimpio", que contendrán un csv de cada plataforma analizada.

- Se trabaja con los csv limpios para comenzar con el EDA. En esta etapa se analizan mediante metodos y gráficos, las variables categoricas y numericas, todas ellas descriptas paso por paso en el archivo notebook "eda.ipynb".

- Finalmente con este analisis realizado, se establecen los 3 KPI pedidos como consigna y se vuelcan los conceptos mas importantes y conclusiones en un dashboard de PowerBi para ser utilizado en la presentacion del mismo.

---

### RESUMEN DEL ANÁLISIS <br>
<br>
El análisis fue basado en las 4 variables requeridas por el cliente:

- NIVEL y MODALIDAD: Se puede concluir que el nivel de principiantes es el más solicitado por los cursantes. Esto, sumado a que la elección de la modalidad ampliamente más elegida fue la de "hacerlo a tu tiempo", muestran que este tipo de ofertas academicas resultan las más flexibles y cómodas a la hora de elegir iniciar un curso o capacitacion.<br>
<br>
- IDIOMAS: Si bien mayoritariamente el idioma predominante en los cursos online es el Inglés, se pudo observar que otros como Español, Italiano, Japones, Frances, tienen un gran promedio de inscriptos con respecto a la cantidad de cursos ofrecidos.<br>
<br>
- PRECIO: Se pudo identificar que los cursos más costosos tienen que ver con disciplinas tales como Ciencias, Computación, Negocios. Tambien se observó que no existe una preferencia marcada en base a sus precios. Probablemente el que decide relizar un curso online esta dispuesto a pagar por la modalidad ofrecida.<br>
<br>
- RATING: El analisis de los cursos por puntaje, no arroja conclusiones certeras, los cursos mejor puntuados son ampliamente variados en categorias, precios y también en la cantidad de inscriptos.
<br>
<br>
- **CATEGORIA:** Si bien se solicitó analizar las variables antes mencionadas, y algunas son relevantes, es de suma importancia agregar y tener en cuenta la categoria.<br> Despues de observar los datos de las 3 plataformas, este aspecto termina siendo el más importante del analisis a la hora de pensar en como afectan a la demanda de los productos vendidos.<br>
La CATEGORIA muestra contundentemente que la disciplina de IT ( Tecnología de la información ) es la más buscada en los MOOCS.<br>
Cursos de programación, ciencia de datos, machine learning, inteligencia artificial, entre otros, encabezan las listas de los más vendidos y populares en las 3 academias.<br>
Por lo que a la hora de sumarse al mercado de cursos online, esta rama de estudios termina siendo muy solicitada y es mayoritariamente la de mejor ventas totales.<br>
También, y no menos importante, es considerar que con la llegada de las nuevas tecnologías y el auge de la inteligencia artificial, el uso de datos y las ciencias de la computación van en constante crecimiento.

---

### KPI

### En linea con los resultados del análisis, se establecen 3 KPI anuales para canalizar las ofertas de cursos y capacitaciones hacia el sector IT:

- **Ventas totales IT**: se calcula como la suma total del precio de los cursos IT que son pagos, por la cantidad de inscriptos. <br>
Objetivo: Lograr incrementar las ventas anuales en un 15%.<br>
<br>
Este KPI permite evaluar el rendimiento y el éxito de las estrategias de ventas de la plataforma en lo que respecta a los cursos de IT. Al establecer un objetivo de incremento anual del 15%, se busca impulsar el crecimiento constante de las ventas en el tiempo.

- **Promedio Inscripciones IT:** se calcula como la suma total de inscriptos a cursos IT sobre la totalidad de cursos ofrecidos *100. <br> Objetivo: incrementar las inscripciones IT en un 20%  anual. <br>
<br>
Este KPI muestra una medida del éxito en la atraccion de inscripciones a los cursos IT, considerando tanto la cantidad de inscriptos como la oferta de cursos disponibles. Al establecer un objetivo anual de incremento del 20%, se busca impulsar el crecimiento sostenido de las inscripciones en el tiempo.

- **Oferta de Cursos IT:**  se expresa como la totalidad de cursos IT que ofrece la plataforma. <br>
Objetivo: aumentar en un 5% la oferta delos cursos IT con respecto al año anterior<br>
<br>
Se busca canalizar la oferta en el rubro IT al haber visto que la demanda de conocimientos y habilidades especializadas es alta debido a la rapida evolucion de la industria. Al aumentar la cantidad de cursos en IT, la plataforma puede abordar esta demanda creciente y captar la atención de un público objetivo interesado en adquirir habilidades en este campo.
