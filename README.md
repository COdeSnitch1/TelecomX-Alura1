# Telecom X

Proyecto desarrollado como parte del Challenge de Data Science de Alura LATAM.

El objetivo es aplicar el proceso **ETL (Extract, Transform, Load)** para transformar datos crudos en un dataset limpio y estructurado, listo para análisis posteriores sobre el abandono de clientes (Churn).

---

## Propósito del análisis

El propósito de este proyecto es preparar y limpiar los datos de clientes de **Telecom X** para facilitar futuros análisis sobre el comportamiento de los usuarios y detectar posibles patrones relacionados con el abandono del servicio.

Para lograrlo se implementó un proceso completo de **ETL**, que permite convertir datos sin procesar en información estructurada y lista para análisis.

---

## Proceso ETL

### Extract
Se obtuvieron los datos desde una fuente externa en formato **JSON** alojada en GitHub.

### Transform
Durante esta etapa se realizaron:

- Normalización de estructuras JSON anidadas
- Limpieza de datos
- Eliminación de registros duplicados
- Conversión de variables categóricas
- Corrección de tipos de datos
- Identificación de valores nulos

### Load
Se generó un **dataset limpio y estructurado**, listo para análisis exploratorio o modelos predictivos.

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Git
- GitHub

---

## Estructura del proyecto

TelecomX-ETL  
│  
├── TelecomX_ETL.ipynb  
├── README.md  
└── telecomx_clean.csv  

---

## Ejemplos de análisis y visualizaciones

Durante el proceso se realizaron visualizaciones para comprender mejor el comportamiento de los clientes.

### Distribución de abandono de clientes
Este gráfico muestra la proporción de clientes que abandonaron el servicio frente a los que permanecen.

### Distribución de cobros mensuales
Permite observar cómo se distribuyen los costos mensuales entre los clientes.

### Relación entre meses de contrato y cobro mensual
Se analiza si existe relación entre la duración del contrato y el valor que pagan los clientes.

---

## Insights iniciales

A partir del análisis preliminar se pueden observar algunos puntos relevantes:

- Existe un grupo significativo de clientes que abandona el servicio.
- Los cobros mensuales presentan una distribución variada entre los usuarios.
- La duración del contrato puede influir en el comportamiento de permanencia de los clientes.

Estos datos permiten preparar el dataset para análisis más profundos en etapas posteriores.

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

git clone https://github.com/TUUSUARIO/telecomx-etl-data-pipeline.git

2. Abrir el archivo **TelecomX_ETL.ipynb** en Google Colab.

3. Ejecutar todas las celdas del notebook para reproducir el proceso ETL completo.

---

## Autor

Proyecto desarrollado por Nicolas Galaz como parte de formación en Data Science de Alura LATAM.
