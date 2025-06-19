# sucursal-preprocesado
# Proyecto de Preprocesamiento de Datos - Ventas por Sucursal

Este repositorio contiene el preprocesamiento de un conjunto de datos simulados para el análisis de ventas por sucursal.

## Archivos incluidos

- `datos_originales/ventas.csv`: Datos de sucursales
- `datos_originales/sucursales.csv`: Datos de alquileres por sucursal
- `datos_preprocesados/ventas_preprocesadas.csv`: Dataset limpio y listo para análisis
- `notebooks/preprocesamiento.ipynb`: Notebook con todos los pasos de limpieza y combinación

## Herramientas utilizadas

- Python
- Jupyter Notebook
- Pandas

## Proceso realizado

1. Carga de los archivos originales
2. Limpieza de valores nulos y duplicados
3. Conversión de fechas
4. Unión de datasets mediante `id_sucursal`
5. Guardado del dataset procesado

