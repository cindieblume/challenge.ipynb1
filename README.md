# challenge.ipynb1
Caso de rentabilidad de 4 tiendas- Análisis
# Análisis de Rentabilidad de Tiendas - Recomendación de Cierre de Tienda

## **Descripción del Proyecto**
Este proyecto tiene como objetivo analizar la rentabilidad y el desempeño de 4 tiendas del cliente Sr. Juan con el fin de recomendar una acción estratégica para optimizar recursos. Específicamente, se analiza cuál tienda debería venderse basándose en factores clave como facturación, popularidad de productos, costos de envío y satisfacción de los clientes.

## **Estructura del Análisis**
El análisis está organizado en los siguientes componentes principales:
1. **Facturación Total por Tienda**: Comparación de los ingresos de cada tienda.
2. **Categorías Más y Menos Populares**: Identificación de las categorías de productos más y menos vendidas en cada tienda.
3. **Calificación Promedio**: Evaluación de la satisfacción de los clientes en cada tienda.
4. **Productos Más y Menos Vendidos**: Análisis detallado de los productos en términos de volumen de ventas e ingresos.
5. **Costo Promedio de Envío por Tienda**: Comparación de los costos operativos por tienda.
6. **Análisis Final y Recomendación**: Conclusión basada en todos los factores analizados.

## **Herramientas y Tecnologías**
El análisis se realizó utilizando las siguientes tecnologías:
- **Python**: Para análisis de datos y generación de gráficos.
- **Bibliotecas utilizadas**:
  - `pandas`: Manejo y análisis de datos.
  - `matplotlib` y `seaborn`: Creación de gráficos y visualizaciones.
  - `numpy`: Cálculos y normalización de datos.

## **Visualizaciones**
El informe incluye visualizaciones clave para facilitar la interpretación de los datos:
1. **Gráfico de Barras**: Comparación de facturación total y otras métricas por tienda.
2. **Gráfico Circular**: Proporción de costos de envío por tienda.
3. **Gráfico Combinado**: Evaluación de múltiples factores (facturación, calificación promedio, costos).
4. **Detalles por Categoría**: Distribución de ventas por categoría de producto.

## **Resultados Clave**
- **Recomendación Estratégica**: La Tienda 4 debe considerarse para la venta debido a:
  - Menor facturación total (1,400,000 unidades monetarias).
  - Altos costos de envío (16,000.7 unidades monetarias en promedio).
  - Calificación promedio más baja (79.92%).
  - Menor diversidad en categorías populares; predominan muebles y electrodomésticos con bajos ingresos por unidad.
- Este análisis respalda la decisión estratégica para enfocar recursos en tiendas más rentables.

## **Cómo Ejecutar este Proyecto**
1. Asegúrate de tener Python instalado en tu sistema.
2. Instala las bibliotecas requeridas:
   ```bash
   pip install pandas matplotlib seaborn numpy
