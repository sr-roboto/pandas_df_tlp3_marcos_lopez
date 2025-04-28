# pandas_df_tlp3_marcos_lopez

## Descripción

En esta actividad se realizan diversas operaciones de análisis de datos
utilizando la biblioteca Pandas de Python. Se trabaja con un dataset de salarios
almacenado en formato SQLite y se realizan diferentes consultas y manipulaciones
de datos.

## Contenido del Repositorio

- **actividad_df.ipynb**: Notebook de Jupyter con los ejercicios y soluciones
- **Salaries.csv**: Archivo CSV con los datos exportados
- **Salaries.sqlite**: Base de datos SQLite con la información original
- **.env/**: Entorno virtual de Python con las dependencias necesarias

## Configuración del Entorno

Para ejecutar este proyecto, se recomienda activar el entorno virtual incluido:

```bash
source .env/bin/activate  # En Linux/Mac
# o
.env\Scripts\activate     # En Windows
```

## Ejercicios Realizados

El notebook contiene los siguientes ejercicios:

1. **Top 10 empleados con mayor salario total (incluyendo beneficios)**

   - Extracción e impresión de los 10 empleados con mayor salario total

2. **Filtrado de empleados con más de 50,000 en horas extra**

   - Manipulación de datos y filtrado de la columna 'OvertimePay'

3. **Conteo de empleados únicos por año**

   - Agrupación y conteo utilizando funciones de Pandas

4. **Análisis de cargos (JobTitle)**

   - Identificación de cargos únicos y los 5 más comunes

5. **Cálculo del salario promedio por año**

   - Agrupación y cálculo de promedios

6. **Exportación de datos a CSV**
   - Guardado de datos procesados en formato CSV

## Requisitos

- Python 3.x
- Pandas
- Jupyter Notebook
- SQLite3

## Autor

Marcos López
