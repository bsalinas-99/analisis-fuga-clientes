# Análisis de Fuga de Clientes – Proyecto Personal

Este proyecto fue desarrollado como parte del Diplomado en Analítica Avanzada de Datos. El objetivo es abordar un problema realista que enfrenta una entidad financiera: la alta tasa de fuga voluntaria de clientes.

La organización no tiene claridad sobre el perfil de los clientes que se fugan ni sobre los motivos de dicha fuga. A partir de una base de datos con múltiples atributos de clientes, se busca identificar patrones de comportamiento y variables que permitan anticipar la fuga.

---

## 📌 Objetivos del trabajo

- Preprocesar la base de datos: limpieza, imputación, detección de problemas.
- Realizar un análisis descriptivo utilizando métricas estadísticas y visualizaciones.
- Crear nuevas variables con potencial predictivo (feature engineering).
- Evaluar y rankear las variables según su capacidad de discriminación.
- Entregar recomendaciones y hallazgos relevantes para la toma de decisiones.

---

## 📊 Descripción de la base de datos

Cada fila representa un cliente y las columnas incluyen:

- Información crediticia en los últimos 3 meses.
- Número de tarjetas de crédito y transacciones online.
- Margen económico generado por el cliente.
- Datos demográficos: edad, ingreso, género, nivel educacional, región.
- Variable objetivo: `FUGA` (`F` = fugado, `NF` = activo).

---

## 🧠 Tecnologías utilizadas

- **Python 3**
- `pandas`, `numpy` para manipulación de datos
- `matplotlib`, `seaborn` para visualización
- `sklearn` para modelado y selección de atributos

---

## 📁 Estructura del repositorio

analisis-fuga-clientes/
│
├── notebook/
│ └── analisis_fuga_clientes_proyecto_personal.ipynb # Análisis completo con preprocesamiento y visualizaciones
│
├── data/
│ └── Base_Fuga_M1.xlsx # Base simulada con información de clientes
│
├── README.md # Descripción general del proyecto

