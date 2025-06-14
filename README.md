


     📌 Alcance del Proyecto
El proyecto abarcará las siguientes tareas:

📁 Recolección de datos públicos sobre pizzerías (ubicación, ratings, reseñas, precios, etc.).

🗺️ Análisis geoespacial para detectar zonas con alta demanda insatisfecha o saturación del mercado.

📊 Análisis de sentimientos y extracción de temas comunes en reviews para entender las preferencias del consumidor.

⚙️ Desarrollo de un sistema de recomendación que, basado en modelos de machine learning, sugiera las mejores ciudades (o zonas dentro de ciudades) para instalar un nuevo restaurante.

📈 Entrega de reportes visuales e interactivos que resuman los hallazgos y recomendaciones del proyecto.

🚫 Fuera del alcance: No se contempla la inversión directa en locales, contratación de personal ni diseño físico del restaurante.



                                            
     🎯 Objetivo del Proyecto

El objetivo de este proyecto es evaluar la viabilidad de emprender un negocio de pizzerías 🍕, considerando el contexto socioeconómico y comercial de distintas regiones. Para ello, se propone:

🔍 Analizar datos de pizzerías en diversas ciudades para identificar aquellas con mayores probabilidades de éxito, en función de la oferta y la demanda local.

🗣️ Estudiar las opiniones y valoraciones de los clientes (reviews) para detectar los servicios o factores clave que influyen en la aceptación y valoración positiva del establecimiento.

🧠 Desarrollar un sistema de recomendación que sugiera ubicaciones óptimas para nuevos locales, basado en patrones de comportamiento del mercado y preferencias de los consumidores.

Este enfoque permitirá tomar decisiones estratégicas basadas en datos, incrementando así las chances de éxito del emprendimiento gastronómico.



    👥 Integrantes y Roles del Proyecto

👨‍💻 Joseph Yersey Bautista Fuentes – Data Engineer

📊 Gonzalo Ariel Sabas – Data Analyst

📊 Rubiolo Gaston – Data Analyst

🧪 Samuel Yang – Data Scientist



KPIs

📈 Incremento Trimestral de la Valoración Promedio

🎯 Objetivo:
Aumentar la puntuación promedio del local en 0.1 puntos por trimestre, basado en las reviews de los usuarios.
(Hasta alcanzar una puntuacion mayor a 4.0 ⭐)

📊 Fórmula:

![alt text](https://github.com/GASabas/PG-Grupo3/blob/main/img/kpi1.png)


📈 Incremento mensual de cantidad de reviews

🎯 Objetivo del negocio:
Incrementar la cantidad total de reseñas recibidas por un local en al menos +2% cada mes.

📊 Fórmula:

![alt text](https://github.com/GASabas/PG-Grupo3/blob/main/img/kpi2.png)

Metodología de Trabajo
📢 Para garantizar una gestión eficiente del proyecto, se aplicará la metodología Scrum:



| HU  | Historia de Usuario                                                     | Tareas                                                                                   |
| --- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| HU1 | Data analyst- Realizar un EDA para entender los datos.                  | ✅ Recopilar datasets <br> ✅ Identificar nulos/duplicados/outliers <br> ✅ Visualizaciones |
| HU2 | Equipo- Definir KPIs para evaluar el sistema.                           | ✅ Identificar métricas clave <br> ✅ Documentar fórmulas y criterios                      |
| HU3 | Equipo- Establecer un repositorio GitHub.                               | ✅ Crear repositorio <br> ✅ Configurar branches y flujos <br> ✅ Documentar estándares     |


| HU  | Historia de Usuario                                                      | Tareas                                                                                           |
| --- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| HU4 | Data Engineer-Crear un pipeline ETL automatizado.                        | ✅ Diseñar flujo ETL <br> ✅ Configurar Data Warehouse/Lake <br> ✅ Implementar carga incremental   |
| HU5 | Equipo- Diseño de un modelo relacional.                                  | ✅ Crear modelo ERD <br> ✅ Implementar en PostgreSQL o BigQuery <br> ✅ Validar integridad vía SQL |
| HU6 | Equipo- Asegurar calidad en los datos.                                   | ✅ Validaciones con Airflow/Prefect <br> ✅ Reportes de calidad <br> ✅ Resolver inconsistencias    |



| HU  | Historia de Usuario                                                             | Tareas                                                                                      |
| --- | --------------------------------------------------------------------------------|---------------------------------------------------                                         |   
| HU7 | Data Analyst- Visualizacion de las recomendaciones en un dashboard interactivo. | ✅ Gráficos de KPIs <br> ✅ Conexión con base de datos <br> ✅Filtros interactivos         |
| HU8 | ML engineer- Entrenar un modelo de recomendación.                               | ✅ Elegir algoritmo <br> ✅ Optimizar hiperparámetros <br> ✅ Evaluar con precisión/recall |
| HU9 | Equipo- desplegar el modelo en producción.                                      | ✅ Crear API con FastAPI <br> ✅ Integrar modelo con dashboard <br> ✅ Probar y optimizar tiempos de respuesta |




STACK TECNOLÓGICO

I. Análisis y Reporte

Análisis Exploratorio de Datos (EDA) y Visualización:
Python:
Pandas y NumPy para la manipulación y el análisis de datos.
Matplotlib y Seaborn para la creación de gráficos estadísticos.
Plotly o Altair para visualizaciones interactivas.
WordCloud para la generación de nubes de palabras.
Jupyter Notebooks: Para la exploración interactiva de los datos, la documentación del proceso de análisis y la presentación de resultados.
Análisis y Procesamiento del Lenguaje Natural (NLP):
Python:
NLTK (Natural Language Toolkit) o spaCy para tareas de NLP como tokenización, lematización, etiquetado de partes del discurso.

II. Modelado de Machine Learning

Desarrollo de Modelos.
Python:
Scikit-learn: Para algoritmos de Machine Learning clásicos (clasificación, regresión, clustering).
TensorFlow o PyTorch: Para la implementación de modelos de Deep Learning (especialmente para tareas de NLP más avanzadas).
Entorno de Desarrollo:
Jupyter Notebooks o Google Colab: Para el desarrollo y experimentación con modelos.
Gestión de Experimentos:
MLflow o TensorBoard: Para el seguimiento de métricas, parámetros y artefactos de los modelos.
Despliegue de Modelos:
Flask o FastAPI (Python): Para crear APIs que permitan la integración de los modelos en otras aplicaciones.
Servicios en la nube : Para el despliegue y escalamiento de modelos en producción.

III. Infraestructura y Herramientas Adicionales

Control de Versiones:
Git: Para la gestión del código fuente y la colaboración en equipo.
GitHub o GitLab: Para el alojamiento de repositorios y la gestión de proyectos.
Contenedorización:
Docker: Para empaquetar las aplicaciones y los modelos en contenedores, facilitando la implementación y la reproducibilidad.
Kubernetes: Para la orquestación de contenedores en entornos de producción.
Computación en la Nube:
AWS, Google Cloud Platform o Azure: Para acceder a recursos de computación escalables, almacenamiento y servicios gestionados (bases de datos, Machine Learning).

Justificación de las Elecciones

Python: Es el lenguaje de programación dominante en ciencia de datos, con una amplia variedad de bibliotecas para la manipulación, el análisis y la visualización de datos, así como para el desarrollo de modelos de Machine Learning.
Pandas y NumPy: Son fundamentales para la manipulación y el análisis eficiente de datos tabulares y numéricos.
Matplotlib y Seaborn: Permiten la creación de visualizaciones claras y efectivas para explorar los datos y comunicar los resultados.
Plotly y Altair: Ofrecen la posibilidad de crear visualizaciones interactivas que facilitan la exploración de los datos por parte de los usuarios.
NLTK y spaCy: Son herramientas poderosas para el procesamiento del lenguaje natural, lo que es esencial para el análisis de sentimientos y la extracción de información de las reseñas.
Scikit-learn: Proporciona una amplia gama de algoritmos de Machine Learning fáciles de usar.
TensorFlow y PyTorch: Son frameworks líderes para el desarrollo de modelos de Deep Learning, que pueden ser necesarios para tareas de NLP más complejas o para el desarrollo de sistemas de recomendación avanzados.
Jupyter Notebooks: Facilitan la exploración interactiva de los datos, la documentación del proceso de análisis y la presentación de resultados.
PostgreSQL: Es una base de datos relacional robusta y de código abierto que ofrece un buen rendimiento y soporte para datos geográficos.
Google BigQuery o Amazon Redshift: Son soluciones de Data Warehouse en la nube que proporcionan una escalabilidad y un rendimiento analítico excelentes para grandes volúmenes de datos.
Apache Airflow: Es una herramienta de orquestación de flujos de trabajo que permite automatizar y programar las tareas de ETL y otros procesos de datos.
Git, GitHub: Son esenciales para el control de versiones y la colaboración en equipo.
Docker y Kubernetes: Facilitan la implementación y el escalamiento de las aplicaciones y los modelos en entornos de producción.
Servicios en la Nube (AWS, Google Cloud, Azure): Proporcionan acceso a una amplia gama de recursos y servicios gestionados que pueden simplificar el desarrollo y la implementación del proyecto.

Estructura del Equipo

Líder de Datos y Analista Principal:
Ingeniero de Datos y Modelado:
Científico de Datos, Visualización y Despliegue:
Roles y Responsabilidades Detalladas

Líder de Datos y Analista Principal:

Gestión general del proyecto, incluyendo la planificación, la asignación de tareas y el seguimiento del progreso.
Comunicación con los stakeholders y presentación de resultados.
Análisis exploratorio de datos (EDA) inicial para comprender los conjuntos de datos y definir las preguntas de investigación.
Definición de los KPIs y métricas de éxito del proyecto.
Coordinación de la integración de datos de diferentes fuentes (Google Maps y Yelp).
Análisis en profundidad de los datos para obtener insights accionables.
Identificación de oportunidades para mejorar las estrategias de marketing y desarrollar sistemas de recomendación.
Supervisión de la calidad de los datos y la implementación del modelo de datos.
Colaboración con el Ingeniero de Datos y Modelado para definir los requisitos de datos y los procesos de ETL.
Colaboración con el Científico de Datos, Visualización y Despliegue para garantizar que los resultados del análisis se comuniquen de manera efectiva.
Habilidades de liderazgo y comunicación.
Python (Pandas, NumPy) y SQL.
Conocimiento general de Machine Learning.
Capacidad para traducir los resultados del análisis en recomendaciones de negocio.

Ingeniero de Datos y Modelado:

Diseño y mantenimiento de la base de datos o sistema de archivos para los datos procesados.
Implementación de los procesos de ETL (Extracción, Transformación, Carga) para preparar los datos para el análisis y el modelado.
Desarrollo de modelos predictivos y de clasificación (si aplica).
Optimización del rendimiento de las consultas y los procesos de datos.
Colaboración con el Científico de Datos y Visualización para proporcionar datos limpios y estructurados.
Implementación de la lógica de negocio para los sistemas de recomendación.
Mantenimiento de la infraestructura de datos.
Python (Pandas, NumPy).
SQL.
Conocimientos de ETL.
Conocimientos de Machine Learning (Scikit-learn).
Habilidades de programación y resolución de problemas.

Científico de Datos, Visualización y Despliegue:

Análisis exploratorio de datos (EDA) en colaboración con el Líder de Datos y Analista Principal.
Creación de visualizaciones de datos informativas y atractivas (Matplotlib, Seaborn, Plotly, WordCloud).
Análisis de sentimiento y procesamiento del lenguaje natural (NLP) de las reseñas (NLTK, spaCy, Transformers).
Evaluación y validación de los resultados del análisis.
Documentación de los hallazgos y los procesos de análisis.
Diseño, implementación y entrenamiento de modelos de Machine Learning (Scikit-learn, TensorFlow, PyTorch) para tareas específicas (ej., sistemas de recomendación).
Optimización y ajuste de modelos para obtener el mejor rendimiento.
Despliegue de modelos para pruebas o demostraciones (Flask/FastAPI - a nivel básico).
Desarrollo de APIs sencillas para acceder a los modelos (si es necesario).
Monitorización del rendimiento de los modelos y reentrenamiento (si el proyecto lo requiere).
Investigación de nuevas técnicas de Machine Learning y su aplicación al proyecto.
Habilidades de programación y resolución de problemas.
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, NLTK, spaCy, Transformers, Scikit-learn, TensorFlow, PyTorch, Flask/FastAPI - a nivel básico).
Sólidas habilidades de visualización de datos.
Conocimientos de estadística y análisis de datos.
Conocimientos de Machine Learning.
Habilidades de comunicación y documentación.

Modelo de Datos:

Un modelo de datos dimensional (esquema estrella o copo de nieve) sería ideal para nuestro Data Warehouse. Este tipo de modelo está optimizado para consultas y análisis de datos, lo que se alinea perfectamente con los objetivos de análisis de sentimientos, predicción y recomendación.

Ventajas del Modelo Dimensional para este Proyecto:

1.⁠ ⁠Optimizado para Consultas Analíticas: Permite realizar agregaciones complejas (ej. sentimiento promedio por tipo de cocina y ciudad) de manera eficiente.
2.⁠ ⁠Facilita la Comprensión: Su estructura simple y lógica facilita que los analistas y científicos de datos comprendan y utilicen los datos.
3.⁠ ⁠Extensibilidad: Es fácil añadir nuevas dimensiones o hechos a medida que el proyecto evoluciona o se incorporan nuevas fuentes de datos (ej. datos de redes sociales, cotizaciones en bolsa).
4.⁠ ⁠Soporte a la Visualización: Compatible con herramientas de BI y visualización que suelen operar bien con esquemas dimensionales.

Tabla de Hechos Central: Fact_Reseña

Esta tabla contendrá las métricas clave y las claves foráneas a las tablas de dimensión. Cada fila representará una reseña individual.

id_reseña (Primary Key): Identificador único de la reseña (puede ser un ID generado si no hay uno consistente entre plataformas).
id_negocio_google (Foreign Key a Dim_Negocio de Google Maps): Identificador del negocio en Google Maps.
id_negocio_yelp (Foreign Key a Dim_Negocio de Yelp): Identificador del negocio en Yelp (se usarán solo las que puedan ser mapeadas, o se usará un id_negocio_unificado).
id_usuario (Foreign Key a Dim_Usuario): Identificador del usuario que escribió la reseña.
id_tiempo (Foreign Key a Dim_Tiempo): Clave para la dimensión de tiempo (fecha de la reseña).
calificacion (Medida): Calificación numérica de la reseña (ej. 1 a 5 estrellas).
sentimiento_score (Medida): Puntuación numérica del sentimiento de la reseña (resultado de tu modelo de NLP).
es_positiva (Medida): 1 si la reseña es positiva, 0 si es negativa/neutra.
utilidad (Medida - si está en los datos): Puntuación de utilidad de la reseña.
diversion (Medida - si está en los datos): Puntuación de diversión de la reseña.
cool (Medida - si está en los datos): Puntuación de "cool" de la reseña.
plataforma_origen (Medida): "Google Maps" o "Yelp" (para diferenciar la fuente).

Tablas de Dimensión:

Estas tablas contendrán atributos descriptivos para filtrar y agrupar los datos de las reseñas.

1.⁠ ⁠Dim_Negocio (Una para Google Maps y otra para Yelp, o una unificada si se logra mapear):

id_negocio_google (Primary Key - para Google Maps)
id_negocio_yelp (Primary Key - para Yelp)
id_negocio_unificado (Primary Key - Altamente Recomendado: Si se puede realizar un matching preciso entre negocios de Google y Yelp, esta sería la clave principal que une ambas fuentes a un solo negocio real. Tendría una id_negocio_google y id_negocio_yelp como atributos).
nombre_negocio
direccion
ciudad
estado
codigo_postal
latitud
longitud
calificacion_promedio_negocio (Ej. de Google Maps o Yelp)
numero_reviews_negocio (Ej. de Google Maps o Yelp)
categorias (ej. 'Italian', 'Pizza', 'Restaurants' - podría ser una tabla de hecho-dimensión si es de tipo muchos a muchos)
es_abierto (para negocios Yelp)
precio_rango (si disponible)
sitio_web
telefono

2.⁠ ⁠Dim_Usuario:

id_usuario (Primary Key)
nombre_usuario (si disponible y anonimizado si es necesario)
ubicacion_usuario (si disponible)
total_reviews_usuario (medida agregada, si es relevante)

3.⁠ ⁠Dim_Tiempo:

id_tiempo (Primary Key, ej. formato YYYYMMDD)
fecha (Fecha completa)
año
mes
dia
dia_semana
trimestre
hora (si la review tiene timestamp)

4.⁠ ⁠Dim_Categoria (Si se manejan categorías como una dimensión separada):

id_categoria (Primary Key)
nombre_categoria (ej. "Pizza", "Italian", "Hotel", "Bar")
tipo_negocio_general (ej. "Comida", "Alojamiento", "Entretenimiento")
