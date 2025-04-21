# Aluraa Análisis de Tiendas de Ventas

Descripción del Proyecto

Este proyecto consiste en un análisis detallado de cuatro tiendas de ventas para determinar cuál es la mejor opción para que el Sr. Juan venda sus productos. El análisis se basa en múltiples factores:

Ingresos totales de cada tienda
Categorías de productos más y menos vendidas
Calificaciones promedio de clientes por tienda
Productos más y menos vendidos
Costo de envío promedio

Datos Utilizados
Los datos provienen de cuatro archivos CSV que contienen información sobre ventas en tiendas diferentes. Los datos incluyen:

Producto
Categoría del producto
Precio
Costo de envío
Fecha de compra
Vendedor
Lugar de compra
Calificación
Método de pago
Cantidad de cuotas
Coordenadas geográficas (latitud y longitud)

Los archivos CSV se encuentran en el siguiente repositorio de GitHub: Repositorio de Datos
Análisis Realizados

1. Análisis de Facturación
Se calculó el ingreso total para cada tienda sumando la columna 'Precio' del DataFrame correspondiente a cada tienda.
2. Ventas por Categoría
Se agruparon los datos por categoría de producto y se contó el número de ventas en cada categoría para cada tienda. Se identificó la categoría más popular en cada tienda.
3. Calificación Promedio de la Tienda
Se calculó la media de la columna 'Calificación' para cada tienda.
4. Productos Más y Menos Vendidos
Se contó cuántas veces aparece cada producto en cada tienda para determinar los productos más y menos vendidos.
5. Costo de Envío Promedio
Se calculó la media de la columna 'Costo de envío' para cada tienda.

Visualizaciones Generadas
Se crearon los siguientes gráficos para visualizar los resultados del análisis:
Ingresos Totales por Tienda: Gráfico de barras vertical.
Ventas por Categoría: Gráfico de líneas.
Calificación Promedio por Tienda: Gráfico de barras horizontal.
Productos Más Vendidos: Gráfico de barras horizontal para los 10 productos más vendidos.
Costo de Envío Promedio: Gráfico de pastel.

Recomendación Final
Basado en los análisis y visualizaciones, se recomienda que el Sr. Juan venda sus productos en la Tienda 2. Esta tienda destaca por:
Altos ingresos totales (COP 1,116,343,500)
Fuerte presencia en categorías demandadas (Muebles y Juguetes)
Alta calificación promedio de clientes (4.80)
Costo de envío promedio competitivo (COP 25,216)
Instrucciones de Instalación y Ejecución

Requisitos

Python 3.x
Bibliotecas: pandas, matplotlib, seaborn (opcional)
