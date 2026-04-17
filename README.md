<img width="1336" height="733" alt="Captura de pantalla 2026-04-17 a las 14 30 57" src="https://github.com/user-attachments/assets/45486729-9dbc-4810-ac8b-170d2b2d8e9b" />


# 📊 Análisis de Datos y Dashboard Interactivo: Kiva Crowdfunding

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Insights-blue?style=for-the-badge)

## 📝 Descripción del Proyecto
Este proyecto aplica la metodología completa de análisis de datos sobre el dataset de microfinanciación de **Kiva**. El objetivo es transformar datos brutos en insights accionables mediante un flujo de trabajo profesional que abarca desde la extracción y limpieza hasta la visualización en un Dashboard interactivo que funciona como una "aplicación personalizada".

## 📂 Estructura del Proyecto
* `DataSet/`: Contiene los archivos fuente (CSV/Excel).
* `Proyecto_Kiva_Analisis.xlsx`: Archivo principal con el análisis y Dashboard.
* `.gitignore`: Configuración para excluir archivos temporales y pesados del repositorio.

## 🛠️ Metodología Aplicada

### 1. Importación y Preparación (ETL)
* **Power Query:** Importación y transformación de datos.
* **Limpieza:** Eliminación de duplicados, gestión de nulos y ordenación cronológica.
* **Formato:** Conversión a objetos de Tabla de Excel para asegurar la integridad de las referencias.

### 2. Análisis Exploratorio y Estadístico
* **Análisis Descriptivo:** Generación de estadísticas clave (media, mediana, desviación estándar) usando la herramienta de *Análisis de Datos*.
* **Funciones Lógicas:** Implementación de columnas calculadas mediante funciones `IF` (SI) para categorizar préstamos.
* **Formato Condicional:** Identificación visual de tendencias y valores atípicos.

### 3. Análisis Avanzado con Tablas Dinámicas
* Creación de tablas dinámicas para resumir métricas de financiamiento por país, sector y tiempo.
* **Campos Calculados:** Implementación de métricas personalizadas (ej. % de éxito de financiación).
* Segmentación de datos para análisis multidimensional.

### 4. Dashboard Interactivo
Diseño de una interfaz de usuario profesional que incluye:
* **KPIs Dinámicos:** Cuadros de texto vinculados a celdas de referencia.
* **Visualizaciones:** Gráficos de barras, líneas y **Mapas Coropléticos** (solucionando limitaciones de tablas dinámicas mediante referencias espejo).
* **Interactividad:** Segmentadores (Slicers) conectados a múltiples tablas para filtrado global.
* **User Experience (UX):** Interfaz limpia, sin cuadrículas ni encabezados, simulando una aplicación de escritorio.

## 📊 Dataset Utilizado
* **Nombre:** Data Science for Good: Kiva Crowdfunding.
* **Fuente:** [Kaggle - Kiva Dataset](https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding)
* **Institución:** Kiva.org

## 🚀 Cómo utilizar este repositorio
1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/TuUsuario/proyecto1-analisisexcel-anaganfornina.git](https://github.com/TuUsuario/proyecto1-analisisexcel-anaganfornina.git)
    ```
2.  Asegúrate de tener instalado **Microsoft Excel**.
3.  Abre el archivo `.xlsx` principal.
4.  Si los datos no cargan, ve a la pestaña **Datos > Consultas y conexiones** y actualiza la ruta de origen.

---
**Autor:** Ana Ganfornina
**Plazo de entrega:** 1 semana
**Nivel alcanzado:** 🟠 Avanzado
