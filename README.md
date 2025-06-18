# 🍕 Proyecto de Viabilidad de Pizzerías: Análisis de Datos y Recomendaciones Estratégicas

Este repositorio contiene el análisis de datos, modelos de Machine Learning y visualizaciones desarrolladas para evaluar la viabilidad de un negocio de pizzerías, identificando ubicaciones óptimas y factores clave de éxito.

---

## 📌 Alcance del Proyecto

El proyecto abarca las siguientes tareas clave:

* **Recolección de Datos:** Adquisición de datos públicos sobre pizzerías (ubicación, ratings, reseñas, precios, etc.) de diversas fuentes.
* **Análisis Geoespacial:** Detección de zonas con alta demanda insatisfecha o saturación del mercado mediante análisis de geolocalización.
* **Análisis de Sentimientos y NLP:** Extracción de temas comunes y análisis de sentimientos en reseñas para comprender las preferencias del consumidor.
* **Sistema de Recomendación:** Desarrollo de un modelo de Machine Learning para sugerir las mejores ciudades o zonas para instalar un nuevo restaurante.
* **Reportes Interactivos:** Creación de dashboards y reportes visuales para resumir hallazgos y recomendaciones.

**Fuera del alcance:** No se contempla la inversión directa en locales, contratación de personal ni diseño físico del restaurante.

---

## 🎯 Objetivo del Proyecto

El objetivo principal es evaluar la viabilidad de emprender un negocio de pizzerías 🍕, considerando el contexto socioeconómico y comercial de distintas regiones. Para ello, se busca:

* **Identificación de Oportunidades:** Analizar datos de pizzerías para identificar ciudades o zonas con mayores probabilidades de éxito, basadas en oferta y demanda.
* **Factores Clave de Éxito:** Estudiar opiniones y valoraciones de clientes (reviews) para detectar servicios o factores que influyen en la aceptación y valoración positiva.
* **Optimización de Ubicaciones:** Desarrollar un sistema de recomendación que sugiera ubicaciones óptimas para nuevos locales, basándose en patrones de comportamiento del mercado y preferencias del consumidor.

Este enfoque permitirá tomar decisiones estratégicas basadas en datos, incrementando las chances de éxito del emprendimiento gastronómico.

---

## 📈 KPIs (Key Performance Indicators)

### Incremento Trimestral de la Valoración Promedio

* **Objetivo:** Aumentar la puntuación promedio del local en 0.1 puntos por trimestre, basado en las reviews de los usuarios (hasta alcanzar una puntuación mayor a 4.0 ⭐).
* **Fórmula:**
    ![KPI 1 - Valoración Promedio](https://github.com/GASabas/PG-Grupo3/blob/main/img/kpi1.png)

### Incremento Mensual de Cantidad de Reviews

* **Objetivo del Negocio:** Incrementar la cantidad total de reseñas recibidas por un local en al menos +2% cada mes.
* **Fórmula:**
    ![KPI 2 - Cantidad de Reviews](https://github.com/GASabas/PG-Grupo3/blob/main/img/kpi2.png)

---

## 📢 Metodología de Trabajo: Scrum

Para garantizar una gestión eficiente del proyecto, se aplicará la metodología **Scrum**.

| HU  | Historia de Usuario                                                              | Tareas                                                                                         |
| --- | -------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| HU1 | Data Analyst - Realizar un EDA para entender los datos.                          | ✅ Recopilar datasets <br> ✅ Identificar nulos/duplicados/outliers <br> ✅ Visualizaciones      |
| HU2 | Equipo - Definir KPIs para evaluar el sistema.                                   | ✅ Identificar métricas clave <br> ✅ Documentar fórmulas y criterios                            |
| HU3 | Equipo - Establecer un repositorio GitHub.                                       | ✅ Crear repositorio <br> ✅ Configurar branches y flujos <br> ✅ Documentar estándares          |
| HU4 | Data Engineer - Crear un pipeline ETL automatizado.                              | ✅ Diseñar flujo ETL <br> ✅ Configurar Data Warehouse/Lake <br> ✅ Implementar carga incremental |
| HU5 | Equipo - Diseño de un modelo relacional.                                         | ✅ Crear modelo ERD <br> ✅ Implementar en PostgreSQL o BigQuery <br> ✅ Validar integridad vía SQL |
| HU6 | Equipo - Asegurar calidad en los datos.                                          | ✅ Validaciones con Airflow/Prefect <br> ✅ Reportes de calidad <br> ✅ Resolver inconsistencias |
| HU7 | Data Analyst - Visualización de las recomendaciones en un dashboard interactivo. | ✅ Gráficos de KPIs <br> ✅ Conexión con base de datos <br> ✅ Filtros interactivos             |
| HU8 | ML Engineer - Entrenar un modelo de recomendación.                               | ✅ Elegir algoritmo <br> ✅ Optimizar hiperparámetros <br> ✅ Evaluar con precisión/recall      |
| HU9 | Equipo - Desplegar el modelo en producción.                                      | ✅ Crear API con FastAPI <br> ✅ Integrar modelo con dashboard <br> ✅ Probar y optimizar tiempos de respuesta |

---

## ⚙️ STACK TECNOLÓGICO

### I. Análisis y Reporte

* **Análisis Exploratorio de Datos (EDA) y Visualización:**
    * **Python:** `Pandas`, `NumPy` para manipulación de datos; `Matplotlib`, `Seaborn` para gráficos estadísticos; `WordCloud` para nubes de palabras.
    * **Jupyter Notebooks:** Para exploración interactiva, documentación y presentación de resultados.
* **Análisis y Procesamiento del Lenguaje Natural (NLP):**
    * **Python:** `NLTK` (Natural Language Toolkit) o `spaCy` para tokenización, lematización, etc.

### II. Modelado de Machine Learning

* **Desarrollo de Modelos:**
    * **Python:** `Scikit-learn` para algoritmos clásicos.
* **Entorno de Desarrollo:**
    * **Jupyter Notebooks** o **Google Colab:** Para desarrollo y experimentación.
* **Gestión de Experimentos:**
    * `MLflow` o `TensorBoard`: Para seguimiento de métricas, parámetros y artefactos de modelos.
* **Despliegue de Modelos:**
    * `Flask` o `FastAPI` (Python): Para crear APIs de integración.
    * **Servicios en la nube:** Para despliegue y escalamiento en producción.

### III. Infraestructura y Herramientas Adicionales

* **Control de Versiones:**
    * `GitHub` o `GitLab`: Para alojamiento de repositorios y gestión de proyectos.
* **Contenedorización:**
    * `Docker`: Para empaquetar aplicaciones y modelos.
* **Computación en la Nube:**
    * **AWS, Google Cloud Platform** o **Azure:** Para recursos escalables y servicios gestionados.

---

## 💡 Justificación de las Elecciones Tecnológicas

* **Python:** Lenguaje dominante en ciencia de datos, con amplias bibliotecas.
* **Pandas y NumPy:** Fundamentales para manipulación eficiente de datos.
* **Matplotlib y Seaborn:** Creación de visualizaciones claras y efectivas.
* **NLTK y spaCy:** Herramientas poderosas para NLP en análisis de reseñas.
* **Scikit-learn:** Amplia gama de algoritmos de ML fáciles de usar.
* **Jupyter Notebooks:** Facilitan la exploración interactiva y documentación.
* **PostgreSQL:** Base de datos relacional robusta y de código abierto con soporte geoespacial.
* **Google BigQuery:** Soluciones de Data Warehouse en la nube para escalabilidad y rendimiento analítico.
* **Apache Airflow:** Orquestación de flujos de trabajo para automatización de ETL.
* **GitHub:** Esenciales para control de versiones y colaboración.
* **Docker:** Facilitan la implementación y el escalamiento en producción.
* **Servicios en la Nube (AWS, GCP, Azure):** Acceso a recursos escalables y servicios gestionados.
* **Joblib:** Para el modelado de Machine Learning

---

## 👥 Estructura del Equipo y Roles

* **Gonzalo Sabas(Líder de Datos y Analista Principal):**
    * **Responsabilidades:** Gestión de proyecto, comunicación con stakeholders, EDA inicial, definición de KPIs, coordinación de integración de datos, análisis profundo, identificación de oportunidades, supervisión de calidad de datos, colaboración con equipo.
    * **Habilidades:** Liderazgo, comunicación, Python (`Pandas`, `NumPy`), SQL, conocimiento general de Machine Learning, traducción de análisis a recomendaciones de negocio.
* **David Yang(Ingeniero de Datos y Modelado):**
    * **Responsabilidades:** Diseño y mantenimiento de base de datos, implementación de procesos ETL, desarrollo de modelos predictivos/clasificación, optimización de consultas, provisión de datos limpios y estructurados, implementación de lógica de negocio para sistemas de recomendación, mantenimiento de infraestructura.
    * **Habilidades:** Python (`Pandas`, `NumPy`), SQL, conocimientos de ETL y Machine Learning (`Scikit-learn`), habilidades de programación y resolución de problemas.
* **Gastón Rubiolo(Científico de Datos, Visualización y Despliegue):**
    * **Responsabilidades:** EDA colaborativo, creación de visualizaciones de datos, análisis de sentimiento y NLP de reseñas, evaluación y validación de resultados, documentación de hallazgos, diseño e implementación de modelos de Machine Learning, optimización y ajuste de modelos, despliegue de modelos (Flask/FastAPI básico), monitoreo de rendimiento, investigación de nuevas técnicas.
    * **Habilidades:** Python (amplio stack de librerías), sólidas habilidades de visualización, conocimientos de estadística y análisis de datos, conocimientos de Machine Learning, comunicación y documentación.

---

## 📊 Modelo de Datos (Dimensional)

Un modelo de datos dimensional (esquema estrella o copo de nieve) será implementado para nuestro Data Warehouse, optimizado para consultas y análisis de datos, alineado con los objetivos de análisis de sentimientos, predicción y recomendación.

### Ventajas del Modelo Dimensional:

1.  **Optimizado para Consultas Analíticas:** Permite agregaciones complejas eficientes.
2.  **Facilita la Comprensión:** Estructura simple y lógica para analistas y científicos de datos.
3.  **Extensibilidad:** Fácil adición de nuevas dimensiones o hechos.
4.  **Soporte a la Visualización:** Compatible con herramientas de BI.

### Tabla de Hechos Central: `Fact_Reseña`

Cada fila representará una reseña individual con métricas clave y claves foráneas.

* `id_reseña` (Primary Key)
* `id_negocio_google` (Foreign Key a Dim_Negocio de Google Maps)
* `id_negocio_yelp` (Foreign Key a Dim_Negocio de Yelp)
* `id_usuario` (Foreign Key a Dim_Usuario)
* `id_tiempo` (Foreign Key a Dim_Tiempo)
* `calificacion` (Medida)
* `sentimiento_score` (Medida)
* `es_positiva` (Medida)
* `utilidad`, `diversion`, `cool` (Medidas)
* `plataforma_origen` (Medida)

### Tablas de Dimensión:

Contendrán atributos descriptivos para filtrar y agrupar datos.

1.  **`Dim_Negocio`**:
    * `id_negocio_google`, `id_negocio_yelp`, `id_negocio_unificado`
    * `nombre_negocio`, `direccion`, `ciudad`, `estado`, `codigo_postal`, `latitud`, `longitud`
    * `calificacion_promedio_negocio`, `numero_reviews_negocio`
    * `categorias`, `es_abierto`, `precio_rango`, `sitio_web`, `telefono`
2.  **`Dim_Usuario`**:
    * `id_usuario`
    * `nombre_usuario`, `ubicacion_usuario`, `total_reviews_usuario`
3.  **`Dim_Tiempo`**:
    * `id_tiempo`, `fecha`, `año`, `mes`, `dia`, `dia_semana`, `trimestre`, `hora`
4.  **`Dim_Categoria`**:
    * `id_categoria`
    * `nombre_categoria`, `tipo_negocio_general`

---

## 🚀 Conclusiones y Próximos Pasos

### Conclusiones Clave:

* "Nuestro proyecto confirma que el análisis de datos masivos es fundamental para la estrategia de negocio. Hemos identificado patrones claros en las preferencias de los consumidores y en la dinámica del mercado de pizzerías en CA/NV."

### Recomendaciones Específicas:

* "Priorizar el estudio de las ciudades de Los Ángeles, San Francisco y Las Vegas para nuevas aperturas, dadas las métricas de sentimiento y competencia."
* "Enfoque en la calidad de los ingredientes y la rapidez en el servicio como factores críticos de éxito."
* "Considerar la expansión en áreas con demanda insatisfecha pero con un alto volumen de reseñas positivas en general."

### Próximos Pasos / Mejoras Futuras:

* Integrar más fuentes de datos (ej. datos demográficos, tráfico peatonal).
* Desarrollar un modelo de recomendación más sofisticado.
* Expandir el análisis a otros tipos de negocios.
"Considerar la expansión en áreas con demanda insatisfecha pero con un alto volumen de reseñas positivas en general."
