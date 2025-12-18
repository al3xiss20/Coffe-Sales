# Coffe-Sales

Este proyecto analiza datos de ventas del sector retail almacenados en Excel, donde se realizan procesos de limpieza y transformación de la información. A partir de estos datos se definen KPIs clave como ventas totales, ticket promedio y margen. La visualización y el análisis se presentan en un dashboard interactivo desarrollado en Power BI, que permite identificar patrones de consumo, productos más rentables y el desempeño por sucursal.

# Dataset Usado
- <a href="https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset">Dataset</a>
- 🗂️ <a href="https://github.com/al3xiss20/Coffe-Sales/blob/d2a6efbc331ba18adf1f28503a875e59bf0c4122/Columnas.png">Columnas</a>

El análisis busca responder preguntas clave como:

- ¿En qué horas del día se concentra la mayor cantidad de ventas?
- ¿Qué franjas horarias generan mayor ingreso total?
- ¿Qué días de la semana presentan mayor y menor facturación?
- ¿Existen patrones estacionales por mes?
- ¿Cuál es el importe promedio por transacción y cómo varía según hora o día?

🔧 Limpieza de datos

El proceso de preparación se realizó en Power Query
- Separación de columnas con Texto en columnas (delimitado por coma).
- Normalización de nombres de columnas y precios.
-Conversión de tipos de datos (fechas, números, texto).
-Eliminación de duplicados.
-Revisión y estandarización de valores faltantes.

 ## Dashboard 
<img width="1897" height="761" alt="Dashboard" src="https://github.com/al3xiss20/Coffe-Sales/blob/main/Dashboard%20p1.png" />
<img width="1897" height="761" alt="Dashboard" src="https://github.com/al3xiss20/Coffe-Sales/blob/main/Dashboard%20p2.png" />



📊 KPIs Definidos

1. Ventas Totales
-Etiqueta: Ventas
-Insight: Representa el ingreso total generado por todas las transacciones. Permite dimensionar el desempeño general del negocio y sirve como referencia principal para evaluar crecimiento y comparar periodos.
________________________________________
2. Ventas por Momento del Día
-Etiqueta: Franja horaria
-Insight: Muestra cómo se distribuyen las ventas según el momento del día. Permite identificar picos de demanda, horas de mayor rentabilidad y oportunidades de optimización operativa.
________________________________________
3. Total de Unidades Vendidas
-Etiqueta: Unidades
-Insight: Indica la cantidad total de productos vendidos. Ayuda a diferenciar entre alto volumen de ventas y alto ingreso, y a analizar la rotación de productos.
________________________________________
4️. Ventas por Día
-Etiqueta: Día de la semana
-Insight: Permite identificar qué días concentran mayor y menor nivel de ventas. Facilita la detección de patrones semanales y la planificación de promociones o ajustes operativos.
________________________________________
5️. Top 5 Cafés Más Vendidos
-Etiqueta: Productos
-Insight: Identifica los cinco cafés con mayor nivel de ventas. Permite reconocer los productos más demandados y evaluar su impacto en los ingresos totales.
________________________________________
6️. Ventas a Través del Tiempo
-Etiqueta: Tendencia temporal
-Insight: Muestra la evolución de las ventas a lo largo del tiempo. Permite detectar tendencias, estacionalidad y cambios en el comportamiento del consumidor.
________________________________________
7️. Precio Unitario Promedio
-Etiqueta: Precio
-Insight: Representa el valor promedio por unidad vendida. Permite analizar el comportamiento de gasto del cliente y evaluar oportunidades de ajuste de precios o estrategias de upselling.
________________________________________
8.	Filtros de Segmentación
- Etiqueta: Filtros dinámicos
- Métrica: Mes, Año, Género, limpiar
- Insight: Permiten un análisis detallado, comparando ventas entre períodos

El análisis de ventas permite identificar patrones claros de consumo a lo largo del tiempo, destacando momentos del día y días de la semana con mayor concentración de ingresos. Los resultados muestran que un grupo reducido de productos concentra la mayor parte de las ventas, mientras que el precio unitario promedio se mantiene estable, reflejando un comportamiento de compra consistente. En conjunto, los insights obtenidos facilitan la toma de decisiones orientadas a optimizar horarios, priorizar productos estratégicos y mejorar el desempeño comercial sin necesidad de incrementar el volumen de clientes.
