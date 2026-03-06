# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX

## 📌 Introducción

La evasión de clientes (Churn) es uno de los principales desafíos para las empresas de telecomunicaciones, ya que implica la pérdida de usuarios que deciden cancelar sus servicios. Comprender las causas de este fenómeno permite a las empresas diseñar estrategias para mejorar la retención de clientes.

El objetivo de este proyecto es analizar los datos de clientes de TelecomX con el fin de identificar patrones asociados con la cancelación del servicio y generar insights que ayuden a reducir la evasión.

---

## 🧹 Limpieza y Tratamiento de Datos

Para preparar los datos para el análisis se realizaron los siguientes pasos:

- Importación de los datos desde una API en formato JSON.
- Conversión de los datos a un **DataFrame de Pandas**.
- Identificación y tratamiento de valores nulos.
- Eliminación de registros inconsistentes.
- Conversión de variables categóricas a variables binarias.
- Estandarización de nombres de columnas para facilitar el análisis.
- Creación de una nueva variable llamada **Cuentas_Diarias**, calculada a partir de los cargos mensuales.

Estas acciones permitieron obtener un dataset limpio y listo para el análisis exploratorio.

---

## 📊 Análisis Exploratorio de Datos

Durante el análisis exploratorio se realizaron diferentes visualizaciones y métricas estadísticas para comprender el comportamiento de los clientes.

Entre los principales análisis realizados se encuentran:

- Distribución de clientes que cancelaron el servicio (**Churn**).
- Análisis de la evasión según variables categóricas como:
  - Género
  - Tipo de contrato
  - Método de pago
  - Servicios contratados
- Análisis de variables numéricas como:
  - Antigüedad del cliente
  - Cargos mensuales
  - Cargos totales

Estos análisis permitieron identificar patrones importantes relacionados con la cancelación del servicio.

---

## 📈 Conclusiones e Insights

A partir del análisis de los datos se identificaron algunos hallazgos relevantes:

- La mayoría de los clientes **no cancelan el servicio**, aunque existe un porcentaje significativo de evasión.
- Los clientes con **contratos mensuales** presentan una mayor probabilidad de cancelar el servicio.
- Los clientes con **menor antigüedad** tienden a abandonar el servicio con mayor frecuencia.
- Los **cargos mensuales más altos** pueden estar asociados con una mayor probabilidad de evasión.

Estos hallazgos permiten comprender mejor el comportamiento de los clientes y los factores asociados a la cancelación del servicio.

---

## 💡 Recomendaciones

Con base en el análisis realizado, se sugieren las siguientes estrategias para reducir la evasión de clientes:

- Incentivar contratos de mayor duración (anuales o bianuales).
- Implementar programas de fidelización para clientes nuevos.
- Analizar la estructura de precios para evitar cargos percibidos como elevados.
- Ofrecer beneficios adicionales a clientes con menor antigüedad para mejorar su experiencia.

Estas acciones pueden contribuir a mejorar la retención de clientes y fortalecer la relación con los usuarios.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 📎 Autor

Proyecto desarrollado por **Diego Caballero** como parte del desafío TELECOMX.
