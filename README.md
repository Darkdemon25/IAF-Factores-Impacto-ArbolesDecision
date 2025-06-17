# 📊 Identificación de Factores Determinantes en el Índice de Alfabetización Financiera (IAF)

Este repositorio documenta el desarrollo integral de un proyecto de investigación enfocado en la identificación de los factores de mayor impacto en el **Índice de Alfabetización Financiera (IAF)** en México. El análisis se fundamenta en la aplicación de modelos de **árboles de decisión** y metodologías de ciencia de datos sobre microdatos derivados de la **Encuesta Nacional de Inclusión Financiera (ENIF)**. Se priorizan las ediciones **2021 y 2024**, complementadas con una fase exploratoria inicial que incorporó datos de **2015 y 2018**.

---

## 📂 Estructura del Proyecto

### 🗃️ 1. Base de Datos Histórica (Versión 2.1)

Esta sección describe la construcción y características de la base de datos central del proyecto:

- **Origen de Datos:** Construida a partir de las ediciones 2021 y 2024 de la ENIF.
- **Normalización y Almacenamiento:** Los datos han sido normalizados y alojados en un sistema gestor de base de datos **MySQL**.
- **Diseño:** La arquitectura de la base de datos está diseñada para permitir escalabilidad y la integración de futuras ediciones de la ENIF.
- **Documentación Asociada:** Se incluye un archivo en formato **Excel** que detalla el diseño de la base de datos y un análisis comparativo entre las ediciones de la encuesta utilizadas.

---

### ⚙️ 2. Preprocesamiento de Datos

Detalla las metodologías empleadas para la preparación de los datos:

- **Procesos Implementados:** Se llevaron a cabo operaciones de depuración, transformación y estandarización de variables. Esto incluyó el tratamiento de valores nulos, la codificación de variables categóricas y la generación de atributos derivados.
- **Plataforma de Desarrollo:** Las rutinas de preprocesamiento fueron desarrolladas en **KNIME Analytics Platform**, y están disponibles como un archivo `.knwf` para su importación directa.

---

### 📈 3. Análisis Exploratorio y Modelado

Describe la fase de análisis y aplicación de modelos:

- **Metodología de Modelado:** Se aplicaron modelos de **árboles de decisión** para identificar y jerarquizar los factores clave que inciden en el IAF.
- **Visualización de Resultados:** Los hallazgos del modelado fueron integrados en un **dashboard interactivo** diseñado para facilitar la interpretación de los resultados por región geográfica y otros criterios relevantes.

---

### 🧪 4. Fase Inicial del Proyecto (Versión 1)

Presenta el trabajo preliminar que sentó las bases para la versión actual:

- **Alcance Inicial:** Construcción de una base histórica preliminar utilizando datos de **2015, 2018 y 2021**.
- **Entorno de Desarrollo:** El desarrollo de esta fase se realizó en **Python** empleando **Visual Studio Code**.
- **Propósito:** Esta versión sirvió como una iteración fundamental para la conceptualización y construcción de la versión final (**V2.1**).
- **Contenido:** Incluye los scripts utilizados para el preprocesamiento de datos y la generación de la base histórica V1.

---

### 📊 5. Dashboard Interactivo

Características del componente de visualización de resultados:

- **Tecnología:** Desarrollado en **Power BI**.
- **Funcionalidad:** Permite la exploración visual de los factores de impacto identificados, con desglose por región.
- **Conectividad:** La información visualizada en el dashboard proviene de archivos **CSV** y **Excel** exportados desde la base de datos **MySQL**, lo que facilita la compatibilidad e integración con **Power BI**.


## 🔧 Herramientas y Tecnologías Utilizadas

- [Python](https://www.python.org/) (pandas, scikit-learn)
- [KNIME Analytics Platform](https://www.knime.com/)
- [Power BI](https://powerbi.microsoft.com/)
- [MySQL](https://www.mysql.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

Este repositorio está estructurado para facilitar su comprensión, replicación y mejora por parte de futuros investigadores, docentes o estudiantes interesados en el análisis de alfabetización financiera con datos abiertos.

