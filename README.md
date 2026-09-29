# Adquisición y Normalización con Pandas
 
## Descripción
 
Este proyecto integra información de ventas proveniente de dos fuentes:
 
- Archivo CSV con transacciones.
- Archivo Excel con catálogo de productos.
 
## Librerías utilizadas
 
- pandas
- openpyxl
- pyarrow
 
## Proceso realizado
 
1. Carga del CSV de transacciones.
2. Carga del Excel de productos.
3. Conversión de fechas a datetime.
4. Tratamiento de valores nulos.
5. Merge mediante id_producto.
6. Creación de la columna total_venta.
7. Exportación a formato Parquet.
 
## Archivo final
 
ventas_normalizadas.parquet
