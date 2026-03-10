# Telecom X

Proyecto de preparación y limpieza de datos desarrollado como parte del Challenge de Data Science de Alura LATAM.

El objetivo es aplicar el proceso **ETL (Extract, Transform, Load)** para transformar datos crudos en un dataset limpio y estructurado listo para análisis posteriores.

---

## Objetivo del proyecto

Preparar los datos de clientes de **Telecom X** mediante un proceso ETL que permita su uso posterior en análisis exploratorio, visualización de datos o modelos predictivos relacionados con el abandono de clientes (Churn).

---

## Proceso ETL

### Extract
Los datos se obtienen desde una fuente externa en formato **JSON** alojada en GitHub.

### Transform
Durante esta etapa se realizaron:

- Normalización de estructuras JSON anidadas
- Limpieza de datos
- Eliminación de duplicados
- Conversión de variables categóricas
- Corrección de tipos de datos
- Análisis de valores nulos

### Load
Finalmente se genera un **dataset limpio y estructurado** listo para análisis y visualización.

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

## Resultados

El proceso ETL permitió:

- transformar datos JSON complejos en una tabla estructurada
- mejorar la calidad y consistencia de los datos
- generar un dataset preparado para futuros análisis de churn

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio

git clone https://github.com/TUUSUARIO/telecomx-etl-data-pipeline.git

2. Abrir el notebook en **Google Colab**.

3. Ejecutar las celdas en orden para reproducir todo el proceso ETL.

---

## Autor

Proyecto desarrollado por Nicolas Galaz como parte de formación en Data Science de Alura LATAM.
