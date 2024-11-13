---

#🐍 **EDA y Análisis: Campaña de Marketing Telefónico Entidad Bancaria**

---

## **Propósito del Proyecto**

Este proyecto tiene como objetivo limpiar y preparar los datos de campañas de marketing telefónico para su posterior análisis exploratorio y visualización. A través de este análisis, se busca extraer información relevante que permita optimizar estrategias de marketing y mejorar la efectividad en futuras campañas.

---

## **Conjunto de Datos**

El análisis se basa en dos conjuntos de datos:

### 1. **bank-additional.csv**

Este dataset contiene información sobre campañas de marketing telefónico realizadas por una entidad bancaria portuguesa. Las campañas incluían múltiples llamadas a los mismos clientes para intentar lograr la contratación de un producto bancario.

#### **Columnas Principales:**

- **age**: Edad del cliente.
- **job**: Profesión del cliente.
- **marital**: Estado civil del cliente.
- **education**: Nivel educativo.
- **default**: Historial de incumplimiento de pagos (1: Sí, 0: No).
- **housing**: Indica si el cliente tiene una hipoteca (1: Sí, 0: No).
- **loan**: Indica si el cliente tiene otros préstamos (1: Sí, 0: No).
- **contact**: Método de contacto (teléfono, móvil, etc.).
- **duration**: Duración en segundos de la última interacción.
- **campaign**: Número de contactos durante la campaña.
- **pdays**: Días desde el último contacto previo.
- **previous**: Número de contactos anteriores.
- **poutcome**: Resultado de la campaña anterior.
- **emp.var.rate**: Tasa de variación del empleo.
- **cons.price.idx**: Índice de precios al consumidor.
- **cons.conf.idx**: Índice de confianza del consumidor.
- **euribor3m**: Tasa de interés Euribor a tres meses.
- **nr.employed**: Número de empleados.
- **y**: Resultado de la campaña (Sí/No).
- **date**: Fecha de la interacción.
- **contact_month**: Mes de la interacción.
- **contact_year**: Año de la interacción.
- **id_**: Identificador único de cada registro.

### 2. **customer-details.xlsx**

Este archivo contiene información adicional de los clientes, segmentada por año de ingreso al banco (2012, 2013 y 2014).

#### **Columnas Principales:**

- **Income**: Ingreso anual del cliente.
- **Kidhome**: Número de niños en el hogar.
- **Teenhome**: Número de adolescentes en el hogar.
- **Dt_Customer**: Fecha en la que el cliente se unió al banco.
- **NumWebVisitsMonth**: Número de visitas mensuales al sitio web.
- **ID**: Identificador único del cliente.

---

## **Procesamiento de los Datos con Python**

La limpieza y transformación de los datos se llevó a cabo en Python utilizando un Jupyter Notebook. Las siguientes librerías fueron empleadas para el análisis y la visualización:

- [**pandas**](https://pandas.pydata.org/): Para la manipulación y análisis de datos estructurados.
- [**numpy**](https://numpy.org/): Para operaciones matemáticas y manejo de matrices.
- [**sklearn**](https://scikit-learn.org/stable/): Para la imputación de valores nulos y técnicas avanzadas de preprocesamiento:
  - [**SimpleImputer**](https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html)
  - [**IterativeImputer**](https://scikit-learn.org/stable/modules/generated/sklearn.impute.IterativeImputer.html)
  - [**KNNImputer**](https://scikit-learn.org/stable/modules/generated/sklearn.impute.KNNImputer.html)
- [**seaborn**](https://seaborn.pydata.org/): Para la visualización de gráficos estadísticos.
- [**matplotlib**](https://matplotlib.org/): Para la visualización básica y personalizada de datos.
- [**plotly**](https://plotly.com/python/): Para visualizaciones interactivas y dinámicas:
  - [**plotly.express**](https://plotly.com/python/plotly-express/)
  - [**plotly.graph_objects**](https://plotly.com/python/graph-objects/)
  - [**plotly.subplots**](https://plotly.com/python/subplots/)
    
---

## **Análisis Exploratorio**

Las preguntas clave que se abordaron en este análisis incluyen:

1. **¿Cuáles son los clientes más propensos a contratar un producto bancario?**
2. **¿Qué factores tienen mayor impacto en el éxito de una campaña de marketing?**
3. **¿Cuál es el perfil demográfico más común entre los clientes del banco?**
4. **¿Cómo influyen los diferentes canales de contacto en la tasa de éxito?**
5. **¿Qué tendencias se observan en el comportamiento de los clientes a lo largo del tiempo?**

---

## **Visualizaciones y Resultados**

Se utilizaron gráficos de barras, gráficos de líneas, diagramas de dispersión y visualizaciones interactivas para representar las respuestas a las preguntas planteadas. Algunas visualizaciones destacadas incluyen:

- **Histogramas**: Para analizar la distribución de variables como edad, ingresos y duración de las llamadas.
- **Gráficos de Líneas**: Para observar tendencias a lo largo del tiempo en la duración de las campañas y la respuesta de los clientes.
- **Diagramas de Dispersión**: Para explorar la relación entre diversas características de los clientes, como la duración de las llamadas y la cantidad de contactos con el cliente.
- **Gráficos Circulares**: Para mostrar la tasa de convwersión de la campaña actual y la campaña anterior.

---

## **Conclusiones y Recomendaciones**

Este análisis proporciona insights valiosos para mejorar la segmentación de clientes y optimizar las futuras campañas de marketing, considerando factores como el perfil demográfico y los canales de contacto más efectivos.

---

## **Estructura del Proyecto**

```
/Marketing_Campaign_Analysis
│
├── data
│   ├── bank-additional.csv
│   └── customer-details.xlsx
│
├── notebooks
│   └── EDA_bank.ipynb
│
├── Informe_Final.pdf
│
└── README.md
```

---

## **Cómo Ejecutar el Proyecto**

1. Clona este repositorio.
2. Abre el archivo `EDA_bank.ipynb` en Jupyter Notebook para explorar el proceso de limpieza y análisis de los datos.
3. Revisa las visualizaciones generadas para obtener las conclusiones clave.

---

## Contacto


- **Email:** [danielroblesaller@gmail.com](mailto:danielroblesaller@gmail.com)
- **LinkedIn:** [Daniel Robles](https://www.linkedin.com/in/danielroblesaller)

---

**¡Gracias por visitar mi repositorio!**

---
