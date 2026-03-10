# Telecom X2 – Predicción de Cancelación de Clientes (Churn)

## Descripción
Este proyecto analiza el comportamiento de los clientes de **Telecom X** con el objetivo de identificar aquellos que presentan mayor riesgo de cancelar el servicio (churn). 
A partir de un conjunto de datos previamente procesado mediante un flujo ETL, se desarrolló un análisis exploratorio y un modelo de **Machine Learning** que permite identificar los factores que influyen en la cancelación de clientes y estimar la probabilidad de abandono.

El proyecto forma parte de un desafío práctico enfocado en aplicar técnicas de **análisis de datos y modelos predictivos** para apoyar la toma de decisiones empresariales.

---

## Objetivos del análisis

- Identificar **clientes con mayor riesgo de cancelación del servicio**.
- Analizar **qué variables influyen más en el churn**.
- Determinar **patrones y perfiles de clientes** asociados a una mayor probabilidad de abandono.

---

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Modelo utilizado

Se implementó un modelo de clasificación basado en **Random Forest**, el cual permite predecir la probabilidad de churn a partir de múltiples variables relacionadas con los clientes, sus contratos y los servicios contratados.

---

## Dataset

Los datos utilizados en el análisis corresponden al dataset tratado en la etapa de ETL.

Archivo utilizado:

`datos_tratados.csv`

Disponible en este repositorio.

---

## Resultados

El análisis permitió identificar que variables como el **tipo de contrato, los cargos mensuales y la antigüedad del cliente** tienen una influencia importante en la probabilidad de cancelación del servicio.

Además, el modelo predictivo permite detectar clientes con mayor riesgo de abandono, lo que puede ayudar a la empresa a implementar estrategias de retención más efectivas.

---

## Autor

Proyecto desarrollado por **Jennifer Soto** como parte de un desafío de análisis de datos aplicado a problemas de negocio.
