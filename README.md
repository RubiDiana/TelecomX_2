<h1 align="center">📊 TELECOM X – PARTE 2: PREDICCIÓN DE CANCELACIÓN (CHURN) 🔍 </h1>

<p align="center">
<a href="#status"><img src="https://img.shields.io/badge/status-completed-green"></a>
<a href="#release-date"><img src="https://img.shields.io/badge/release_date-Agosto-yellow"></a>
<a href="#python"><img src="https://img.shields.io/badge/python-blue"></a>
</a>
</p>

---

## 📋 Propósito del proyecto

Este proyecto tiene como objetivo principal desarrollar un modelo predictivo para identificar clientes con alta probabilidad de cancelar su servicio (churn) en Telecom X. Mediante el análisis de diversas variables demográficas, de servicio y de uso, buscamos comprender los factores clave que impulsan el churn y utilizar este conocimiento para implementar estrategias de retención efectivas.


## 📁 Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

`📂TelecomX_2/`

`├── 📄TelecomX_2.ipynb` – Notebook principal con todo el análisis y modelado.

`├── 📄datos_limpios.csv` – Fuente de datos procesados en la primera parte.

`└── 📄README.md` – Descripción del proyecto


## ⚙️ Preparación de los Datos

El proceso de preparación de datos incluyó las siguientes etapas:

1.  Carga de Datos
2.  Clasificación de Variables
3.  Eliminación de Columnas Irrelevantes
4.  Estandarización de Valores
5.  Codificación (Encoding)
6.  Normalización/Estandarización
7.  Análisis de Correlación y Multicolinealidad
8.  Separación de Datos en conjuntos de entrenamiento y prueba


## 🤖 Modelado Predictivo

Se entrenaron y evaluaron los siguientes modelos predictivos:

*   **Regresión Logística**
*   **Random Forest Classifier**
*   **Gradient Boosting Classifier**


## 🛠️ Herramientas utilizadas

Este proyecto utilizó las siguientes bibliotecas de Python:

*   **pandas**: Para manipulación y análisis de datos.
*   **numpy**: Para operaciones numéricas.
*   **seaborn**: Para visualización de datos estadísticos.
*   **matplotlib**: Para la creación de gráficos estáticos.
*   **sklearn**: Para modelado predictivo, preprocesamiento de datos y evaluación de modelos.
*   **imblearn**: Para manejar el desbalance de clases usando técnicas como SMOTE.
*   **statsmodels**: Para análisis estadístico, incluyendo el cálculo de VIF.


## 🚀 Instrucciones para Ejecutar el Cuaderno

Para ejecutar el cuaderno y replicar el análisis, sigue estos pasos:

1. Clona el repositorio:
```bash
git clone https://github.com/RubiDiana/TelecomX_2.git
cd TelecomX_2
```

2. Ejecuta el notebook:
   
    Puedes abrir y ejecutar el archivo .ipynb en:
    - Google Colab
    - Jupyter Notebook
    - VSCode (con extensión de Python)


## 👤 Autor
- Github: [@RubiDiana](https://github.com/RubiDiana)
