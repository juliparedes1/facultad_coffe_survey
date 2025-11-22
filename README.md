# Análisis de Mercado: La Gran Prueba de Sabor de Café (James Hoffmann)

## Descripción del Proyecto
Este proyecto simula un escenario de consultoría para un grupo inversor interesado en abrir una cafetería en EE.UU. Utilizando Python y Pandas, se analizaron los datos de la encuesta "The Great American Coffee Taste Test" (realizada por el experto James Hoffmann en 2023 con +4,000 participantes) para identificar preferencias de consumo, demografía y hábitos.

El objetivo principal es extraer insights accionables para diseñar una estrategia de mercado informada.

##  Tecnologías Utilizadas
* **Python**
* **Pandas:** Manipulación, limpieza y transformación de datos.
* **NumPy:** Operaciones numéricas.
* **Matplotlib:** Visualización de datos.

##  Características del Análisis
El notebook incluye un flujo de trabajo de Data Analytics completo:

1.  **Ingesta de Datos:** Descarga programática del dataset desde el repositorio oficial.
2.  **Limpieza de Datos (Data Cleaning):**
    * Manejo de valores nulos (NA).
    * Normalización de columnas con respuestas múltiples (uso de `split` y `explode` para normalización a 1ra forma normal).
    * Limpieza de cadenas de texto (stripping).
3.  **Automatización:** Creación de funciones personalizadas (`procesar_columna` y `filtrar_columna_valor`) para reutilizar lógica de limpieza y filtrado.
4.  **Exploración Demográfica:** Análisis de distribución por edad y género.
5.  **Visualización:**
    * Gráfico de torta para distribución etaria.
    * Gráficos de barras segmentados para relacionar edad con tipo de café favorito.

## 📊 Principales Hallazgos (Insights)
* **Demografía Clave:** El segmento de edad predominante en la encuesta es de **25 a 34 años** (aprox. 50% de la muestra), seguido por el grupo de 35-44 años.
* **Hábitos de Consumo:** La gran mayoría de los encuestados (más de 3,600) consumen café en casa ("At home"), lo que sugiere un mercado fuerte para la venta de grano o equipamiento doméstico.
* **Preferencias:** Se identificaron patrones claros de preferencia de tipos de café (Pourover, Espresso, Latte) cruzados con grupos etarios.

##  Cómo ejecutar este proyecto
1.  Clona este repositorio.
2.  Instala las librerías necesarias:
    ```bash
    pip install pandas matplotlib numpy requests
    ```
3.  Abre el archivo `.ipynb` en Jupyter Notebook, VS Code o Google Colab.
4.  Ejecuta las celdas secuencialmente. El script descargará automáticamente el archivo `coffee_survey.csv`.

---
**Autor:** Julian Paredes
*Proyecto realizado para la materia Programación 2 - 2025*
