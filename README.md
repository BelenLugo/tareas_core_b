# tareas_core_b
This is my core tasks repository.

# Análisis de Ventas de Supermercado

Este proyecto realiza un análisis de datos sobre las ventas de un supermercado utilizando Python, pandas y NumPy. Se carga un conjunto de datos desde un archivo CSV, se limpian y procesan los datos, y se generan insights relevantes a través de estadísticas descriptivas y visualizaciones.

## Contenido

- [Instalación](#instalación)
- [Uso](#uso)
- [Análisis Realizados](#análisis-realizados)
- [Exploración de Datos](#exploración-de-datos)
- [Resultados](#resultados)
- [Contribuciones](#contribuciones)

## Instalación

Asegúrate de tener instalado Python en tu máquina. Este proyecto utiliza las siguientes bibliotecas:

- pandas
- NumPy

Puedes instalarlas utilizando pip:

```bash
pip install pandas numpy


## Instalación

Clona este repositorio:
bash
Copy code
git clone https://github.com/tu_usuario/tu_repositorio.git
Navega al directorio del proyecto:
bash
Copy code
cd tu_repositorio
Ejecuta el script de análisis:
bash
Copy code
python tu_script.py
Asegúrate de que el archivo supermarket_sales.csv esté en el directorio data o actualiza la ruta en el script.


## Análisis Realizados

El script realiza las siguientes tareas:

Carga del archivo CSV con los datos de ventas.
Inspección inicial del DataFrame (visualización de las primeras y últimas filas, información general, estadísticas descriptivas).
Identificación y manejo de datos faltantes y duplicados.
Cálculo de nuevos indicadores, como el total después de impuestos y la clasificación de ingresos en categorías.
Exploración de categorías como tipo de cliente, género, línea de producto, métodos de pago y ciudad.
Agrupaciones para analizar las ventas por línea de producto y sucursal, así como la media de ventas.
Aplicación de funciones personalizadas para calcular proporciones de ventas por línea de producto.

## Exploración de Datos
El análisis incluye la exploración de categorías relevantes en los datos:

python
Copy code
print('Customer type: ', df['Customer type'].unique())
print('Gender: ', df['Gender'].unique())
print('Product line: ', df['Product line'].unique())
print('Payment: ', df['Payment'].unique())
print('City: ', df['City'].unique())

## Resultados
Los resultados del análisis proporcionan insights valiosos sobre las ventas del supermercado, como:

Ventas totales por línea de producto.
Ventas totales por sucursal.
Ventas promedio por línea de producto.
Proporciones de ventas que permiten entender la contribución de cada línea de producto.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, por favor crea un fork del repositorio y envía un pull request.