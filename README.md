# 🕸️ PYTHON WEB SCRAPING: EXTRACCIÓN Y USO DE DATOS WEB

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![Requests](https://img.shields.io/badge/Requests-0077B6?style=flat&logo=python&logoColor=white)](https://requests.readthedocs.io/en/latest/)  
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-000000?style=flat&logo=python&logoColor=white)](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

Este proyecto se enfoca en el **Web Scraping** (raspado web), la práctica de **recolección automática de información de Internet**, utilizando Python. El objetivo es simular la extracción de datos de una página de venta de autos para crear una base de datos accionable en proyectos posteriores de Machine Learning.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Introducción al Web Scraping
- **Definición:** **Web Scraping** es la simulación de la navegación humana en la web mediante programas para la recolección automática de datos.
- **Caso de Uso:** La información extraída (imágenes, kilometraje, valor, año del vehículo) servirá para:
    * **Machine Learning:** Usar las imágenes para proyectos de Visión por Computadora (inferido).
    * **Modelos de Regresión:** Generar modelos predictivos (ej. predecir el precio del vehículo en función del kilometraje y el año) para analizar el comportamiento del mercado.

### 2️⃣ Metodología de Extracción (Scraping)
- **Extracción del HTML:** Uso de librerías para descargar y analizar el contenido HTML de la página objetivo (ej. una página de autos del Atlántico).
- **Navegación:** La técnica implica simular la acción de ir página por página para extraer la información completa.
- **Identificación de Elementos:** El proceso se basa en identificar los *tags* HTML (etiquetas, clases) que contienen la información deseada (ej. precio, año, kilometraje).

### 3️⃣ Almacenamiento y Salida de Datos
- **Estructuración con Pandas:** Los datos extraídos se almacenan y estructuran en un **DataFrame de Pandas**.
- **Exportación a CSV:** El DataFrame final se exporta como un archivo **CSV** (`dataset.csv`).
- **Almacenamiento Persistente:** Se demuestra la capacidad de guardar este archivo CSV en una ubicación externa (ej. Google Drive) para su uso posterior en otros proyectos de Data Science.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Requests**   | Realiza las peticiones HTTP para descargar el contenido de la página web|
| **BeautifulSoup** | Analiza el documento HTML descargado y permite la navegación por el árbol de etiquetas para encontrar datos específicos (inferido por ser la herramienta estándar de análisis)|
| **Pandas**     | Estructura los datos extraídos en un DataFrame y gestiona la exportación a CSV|

---

## 🎯 Objetivo del Proyecto
Dominar la técnica de **Web Scraping** para transformar contenido no estructurado (sitios web) en **bases de datos limpias y estructuradas**. El objetivo final es obtener datos de mercado de vehículos para alimentar modelos de **Regresión** y entender el comportamiento de precios en el mercado automotriz.

---

## 📈 Resultados Clave
- Se realiza con éxito la **recolección automática de datos** de una página web.
- Se genera un **archivo CSV** (`dataset.csv`) que contiene la información relevante (km, valor, año, etc.) de múltiples páginas.
- Se demuestra la conexión entre la extracción de datos (Web Scraping) y su utilidad práctica en **proyectos de Machine Learning** y análisis de mercado.

