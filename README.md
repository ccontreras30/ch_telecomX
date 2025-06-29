# ch_telecomX
Challenge ONE Data Science - Telecom X
# Análisis de Evasión de Clientes (Churn) – TelecomX

Este proyecto tiene como objetivo identificar patrones de abandono de clientes (churn, desde ahora evasión) en una empresa de telecomunicaciones ficticia llamada **TelecomX**. A través del análisis de datos reales anonimizados y herramientas de Python, se generan insights estratégicos que pueden ser utilizados para mejorar la retención de clientes.

---

## Descripción del Proyecto

La evasión representa la pérdida voluntaria de clientes. Detectar sus causas es fundamental para tomar decisiones inteligentes de negocio.

Este proyecto:

- Limpia, transforma y estructura los datos extraídos desde una API y un archivo JSON.
- Analiza variables categóricas y numéricas asociadas a la evasión.
- Ofrece recomendaciones concretas para reducir la pérdida de clientes.
- Finaliza con un informe final documentado y visualmente soportado.

---

## Funcionalidades implementadas con Python

El flujo de trabajo, incluye todo lo solicitado para el desarrollo del proyecto:

### Carga de Datos
- Extracción de datos desde API REST
- Lectura de archivos `.json` y `.md` en Google Colab
- Conversión de estructuras anidadas a `pandas.DataFrame`

### Limpieza y Preprocesamiento
- Eliminación de duplicados y valores nulos
- Conversión de columnas numéricas
- Estandarización de valores categóricos (`sí`/`no`, `yes`/`no`)
- Creación de nuevas variables como `Gasto_Diario`

### Análisis Exploratorio de Datos (EDA)
- Distribución de `Evasion` en gráficos circulares y de barras
- Comparación cruzada con variables categóricas (`Tipo_Contrato`, `Método_Pago`, `Genero`)
- Evaluación de variables numéricas como `Gasto_Total`, `Meses_Contrato`
- Estadísticas por grupo (`Evasion = 0` y `1`)

### Visualizaciones
- `matplotlib` y `seaborn` para histogramas, countplots y análisis por grupos
- Comparación de métricas con tablas formateadas y gráficos por categoría

---

## Acceso y Ejecución en Google Colab

Puedes ejecutar este proyecto directamente desde [Google Colab](https://colab.research.google.com/) copiando o clonando este repositorio. Para comenzar:

```bash
!git clone https://github.com/ccontreras30/ch_telecomX.git
%cd nombre-del-repo
```
Luego, abre el archivo TelecomX_LATAM.ipynb y ejecuta cada celda paso a paso.
Requisitos:
Python 3.10+
Pandas, NumPy, Seaborn, Matplotlib
Google Colab (entorno ya preconfigurado)

---

## Informe Final

El análisis se resume en un informe estructurado que incluye:
- Introducción al problema de Evasión
- Tratamiento y transformación de datos
- Comparación de clientes que abandonan vs los que permanecen
- Estadísticas, visualizaciones y distribución por grupo
- Recomendaciones estratégicas para mitigar la evasión

El informe está disponible:
- Como celda Markdown al final del notebook (.ipynb)

---

## Lenguaje utilizado

Todo el análisis está construído en Python 3, utilizando librerías como:
- pandas -> para manipulación de datos
- numpy -> para cáculos numéricos
- matplotlib y seaborn -> para visualización de datos
- json -> para manejo de archivos estructurados

---

## Desarrollador del Proyecto

https://www.linkedin.com/in/carlos-contreras-lillo
