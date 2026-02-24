# 📊 Challenge Data Science - Alura Store Latam 🛍️

Este proyecto es parte del **Challenge de Data Science** organizado por Alura Latam. El objetivo principal es analizar el desempeño comercial de una cadena de tiendas minoristas para apoyar la toma de decisiones estratégicas del dueño, el Sr. Juan.

## 📝 Descripción del Proyecto

El proyecto consiste en un análisis exploratorio de datos (EDA) de cuatro sucursales distintas (Tienda 1, 2, 3 y 4). Se procesaron grandes volúmenes de datos de ventas para responder a una pregunta de negocio crítica: **¿Qué tienda debería ser vendida o cerrada para optimizar los activos de la empresa?**

El análisis abarca desde la limpieza de datos hasta la visualización geográfica, pasando por métricas clave como facturación y satisfacción del cliente.

## 🚀 Características y Análisis Realizados

El notebook incluye el desarrollo de los siguientes puntos:

* **Análisis de Facturación:** Cálculo de ingresos totales por tienda para identificar la más y menos rentable.
* **Ventas por Categoría:** Desglose de los productos más populares (Electrónicos, Muebles, etc.).
* **Satisfacción del Cliente:** Evaluación de la calidad del servicio mediante el promedio de calificaciones.
* **Costos Operativos:** Análisis del costo promedio de envío.
* **Visualización de Datos:** Gráficos de barras, pastel y dispersión generados con **Matplotlib**.
* **Análisis Geográfico (Bonus):** Mapeo de coordenadas (latitud/longitud) para entender la distribución territorial de las ventas.

## 🛠️ Tecnologías Utilizadas

* **Python 3**
* **Pandas:** Para la manipulación y análisis de estructuras de datos.
* **Matplotlib:** Para la generación de gráficos y visualizaciones.
* **Google Colab:** Entorno de desarrollo en la nube.

## 📦 Cómo ejecutar el proyecto

Para reproducir este análisis en tu máquina local o en la nube:

1.  **Clonar el repositorio:**
    ```bash
    git clone <https://github.com/77marco/Challenge-Data-Science-Alura>
    ```
2.  **Abrir el Notebook:**
    Sube el archivo `AluraStoreLatam_1.ipynb` a [Google Colab](https://colab.research.google.com/) o ábrelo localmente con Jupyter Notebook.
3.  **Instalar dependencias:**
    El entorno de Colab ya incluye las librerías necesarias. Si lo corres localmente, asegúrate de instalar:
    ```bash
    pip install pandas matplotlib
    ```
4.  **Ejecutar las celdas:**
    Corre las celdas en orden secuencial. Los datos se cargan automáticamente desde los repositorios remotos configurados en el código.

## 🔍 Hallazgos Principales

* **Tienda con mayores ingresos:** Tienda 1.
* **Tienda con mejor calificación:** Tienda 3.
* **Recomendación estratégica:** Se sugirió la venta de la **Tienda 4** debido a que presenta el rendimiento financiero más bajo del grupo, compartiendo el mismo territorio geográfico que las tiendas más fuertes, lo que la hace prescindible.
* **Geografía:** Se descubrió que todas las tiendas operan en las mismas coordenadas exactas, compitiendo por el mismo mercado.

## ✒️ Autor

* **[Marco Corral]** - *Desarrollador y Analista de Datos*
* Desarrollado durante el programa ONE (Oracle Next Education) y Alura Latam.

---
⭐️ Si este proyecto te pareció útil o interesante, ¡no dudes en darle una estrella en GitHub!
