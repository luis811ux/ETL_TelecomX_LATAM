# 📊 Telecom X - Análisis de Evasión de Clientes

## 🧭 Resumen del contenido del README.md

1. [Descripción del Proyecto](#descripcion-del-proyecto) 
2. [Objetivos](#objetivos) 
3. [Tecnologias y Librerias Utilizadas](#tecnologias-y-librerias-utilizadas)
4. [Estructura del Proyecto](#estructura-del-proyecto)  
5. [Como Ejecutar el Proyecto](#como-ejecutar-el-proyecto)  
6. [Contenido del Analisis](#contenido-del-analisis)
7. [Informe Final](#informe-final)  
8. [Contribuciones](#contribuciones)  
9. [Licencia](#licencia)


<h2 id="descripcion-del-proyecto">📊 1. Descripción del Proyecto</h2>


Este proyecto forma parte del desafío de análisis de datos en **Telecom X**, una empresa que enfrenta una alta tasa de cancelación de clientes. El objetivo principal es comprender los factores que influyen en la pérdida de clientes mediante análisis exploratorio de datos (EDA), procesamiento y visualización, con el fin de respaldar decisiones estratégicas y desarrollar modelos predictivos.

---

<h2 id="objetivos">📌 2. Objetivos</h2>

- Entender las causas de la evasión de clientes.
- Realizar un proceso ETL completo: Extracción, Transformación y Carga de datos.
- Generar visualizaciones efectivas para detectar patrones.
- Identificar insights clave para reducir la tasa de cancelación.
- Elaborar un informe con recomendaciones estratégicas.

---

<h2 id="tecnologias-y-librerias-utilizadas">3. 🛠️ Tecnologías y Librerías Utilizadas</h2>

El análisis se realizó en un entorno de Python basado en la nube (Google Colab), utilizando las siguientes bibliotecas:

- `pandas` – Manipulación y análisis de datos.
- `matplotlib.pyplot` – Visualización de datos.
- `numpy` – Cálculos estadísticos y manejo de arrays.

---

<h2 id="estructura-del-proyecto">🧱 4. Estructura del Proyecto</h2>

```
Telecom_X_Churn_Analysis/
├── data/
│   └── TelecomX_Data.json             # Dataset con la información de los clientes de Telecom X
├── docs/
│   └── TelecomX_diccionario.md        # Diccionario de datos: descripción de cada columna del dataset
├── notebooks/
│   └── TelecomX_LATAM.ipynb           # Notebook principal con todo el análisis y el informe final
├── README.md                          # Documento descriptivo del proyecto
├── requirements.txt                   # Lista de dependencias y librerías necesarias para reproducir el análisis
└── LICENSE                           # Licencia MIT del proyecto
```

<h2 id="como-ejecutar-el-proyecto">🚀 5. Cómo Ejecutar el Proyecto</h2>

Sigue estos pasos para ejecutar el proyecto y visualizar el informe final en Google Colab:

1. **Descargar el proyecto**
   - Dirígete al repositorio: `https://github.com/luis811ux/ETL_TelecomX_LATAM`
   - Haz clic en **Code > Download ZIP**.
   - Extrae el contenido del archivo `.zip` en tu equipo.

2. **Abrir Google Colab**
   - Ve a [Google Colab](https://colab.research.google.com/).
   - En la pestaña **"Subir"**, carga el archivo `TelecomX_LATAM.ipynb` desde la carpeta descomprimida.

3. **Subir archivos necesarios**
   - Desde el panel lateral izquierdo en Colab, sube:
     - `TelecomX_Data.json`
     - `TelecomX_diccionario.md`

4. **Conectarse al entorno de ejecución**
   - Haz clic en **"Conectar"** (parte superior derecha) para activar el entorno de Colab.

5. **Ejecutar el notebook**
   - Verifica que estén disponibles las siguientes bibliotecas (ya preinstaladas en Colab):
     ```python
     import pandas as pd
     import matplotlib.pyplot as plt
     import numpy as np
     ```
   - Luego, presiona `Ctrl + F9` o selecciona **"Entorno de ejecución > Ejecutar todo"**.

📌 **Resultado esperado:**
- Visualización de los *dataframes* procesados.
- Gráficos del análisis exploratorio.
- Informe final con conclusiones y recomendaciones al final del notebook.

---

<h2 id="contenido-del-analisis">📈 6. Contenido del Análisis</h2>

### 🔹 Introducción
Este análisis aborda la problemática del "Churn" o cancelación de clientes en Telecom X, aplicando herramientas de Python para extraer información valiosa que contribuya a estrategias de retención.

### 🔹 Limpieza y Tratamiento de Datos
- Carga del archivo `TelecomX_Data.json`.
- Tratamiento de valores nulos y conversión de tipos de datos.

### 🔹 Análisis Exploratorio (EDA)
- Estadísticas descriptivas.
- Visualizaciones para estudiar correlaciones y patrones de cancelación.

### 🔹 Conclusiones e Insights

Se destacan patrones relevantes como:

1. **Análisis de Desafiliados**
2. **Análisis de Evasión por Tipo de Contrato y Cargo Mensual**
3. **Análisis por Edad Adulta**
4. **Análisis de Evasión según Dependientes**
5. **Análisis por Estado de Pareja**
6. **Análisis por Antigüedad**

> **Conclusión general**:  
> La población que tiende a desertar de Telecom X corresponde a personas jóvenes, sin hijos y sin pareja, con inestabilidad financiera. Prefieren contratos mensuales y suelen cancelar el servicio en los primeros tres meses.

### 🔹Recomendaciones
Se proponen estrategias dirigidas a retener a este grupo de clientes, considerando sus características y patrones de cancelación.

---

<h2 id="informe-final">📄 7. Informe Final</h2>

Todo el análisis y sus conclusiones se encuentran documentados dentro del notebook `TelecomX_LATAM.ipynb`, el cual incluye:

- Código limpio y comentado.
- Visualizaciones explicativas.
- Estructura clara y ordenada para facilitar la lectura.

---

<h2 id="contribuciones">🤝 8. Contribuciones</h2>

¡Contribuciones y sugerencias son bienvenidas!  
Puedes abrir un **Issue** o enviar un **Pull Request** con tus mejoras.

---

<h2 id="licencia">📜 9. Licencia</h2>

Este proyecto se distribuye bajo la licencia MIT.  
Consulta el archivo `LICENSE` para más detalles.

