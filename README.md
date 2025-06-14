# 📊 Identificación de Factores de Impacto en el IAF mediante Árboles de Decisión

Este repositorio contiene el desarrollo completo del proyecto orientado a identificar los factores de mayor impacto en el **Índice de Alfabetización Financiera (IAF)** en México, mediante el análisis de datos utilizando modelos de **árboles de decisión** y herramientas de ciencia de datos. El proyecto toma como base los microdatos proporcionados por la **Encuesta Nacional de Inclusión Financiera (ENIF)**, principalmente de las ediciones **2021 y 2024**, aunque también incluye una fase inicial con datos de **2015 y 2018**.

---

## 📂 Contenido del Proyecto

### 🗃️ 1. Base de Datos Histórica (Versión 2.1)
- Construida a partir de las ediciones **2021 y 2024** de la ENIF.
- Normalizada y alojada en un gestor de base de datos **MySQL**.
- Diseñada para permitir su escalabilidad con futuras ediciones.
- Incluye un archivo en **Excel** con el diseño de la base y un análisis comparativo entre las encuestas.

### ⚙️ 2. Preprocesamiento de la Información
- Depuración, transformación y estandarización de variables.
- Tratamiento de valores nulos, codificación de variables categóricas y creación de atributos derivados.
- Desarrollado en **KNIME**, disponible como archivo `.knwf` para importar directamente desde la plataforma.

### 📈 3. Análisis Exploratorio y Modelado
- Aplicación de modelos de **árboles de decisión** para identificar los factores clave que influyen en el IAF.
- Resultados utilizados para alimentar un **dashboard interactivo** que permite su interpretación por región y otros criterios.

### 🧪 4. Primera Fase del Proyecto (Versión 1)
- Construcción inicial de la base histórica con datos de **2015, 2018 y 2021**.
- Desarrollo realizado en **Python** utilizando **Visual Studio Code**.
- Esta versión sirvió como base para iterar y construir la versión final **2.1**.
- Incluye scripts de preprocesamiento y generación de la base histórica V1.

### 📊 5. Dashboard Interactivo
- Desarrollado en **Power BI**.
- Permite explorar visualmente los factores de impacto por región.
- Conectado directamente a la base de datos en **MySQL** para integrar los datos procesados.

---

## 🔧 Herramientas y Tecnologías Utilizadas

- [Python](https://www.python.org/) (pandas, scikit-learn)
- [KNIME Analytics Platform](https://www.knime.com/)
- [Power BI](https://powerbi.microsoft.com/)
- [MySQL](https://www.mysql.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

Este repositorio está estructurado para facilitar su comprensión, replicación y mejora por parte de futuros investigadores, docentes o estudiantes interesados en el análisis de alfabetización financiera con datos abiertos.

