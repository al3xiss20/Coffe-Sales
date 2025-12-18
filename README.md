# Coffe-Sales

Este proyecto analiza datos de ventas del sector retail almacenados en Excel, donde se realizan procesos de limpieza y transformación de la información. A partir de estos datos se definen KPIs clave como ventas totales, ticket promedio y margen. La visualización y el análisis se presentan en un dashboard interactivo desarrollado en Power BI, que permite identificar patrones de consumo, productos más rentables y el desempeño por sucursal.

# Dataset Usado
- <a href="https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset">Dataset</a>
- 🗂️ <a href="https://github.com/al3xiss20/Data-Analysis-Dashboard/blob/main/Colum.png">Columnas</a>

El análisis busca responder preguntas clave como:

- ¿Cuáles son las sucursales más rentables?
- ¿Qué productos generan mayores ingresos?
- ¿Cuál es el ticket promedio de compra?
- ¿Qué método de pago es más utilizado?
- ¿Qué tan satisfechos están los clientes?

🔧 Limpieza de datos

El proceso de preparación se realizó en Excel (<a href="https://github.com/al3xiss20/Data-Analysis-Dashboard/blob/main/1.png">Base</a>):
- Separación de columnas con Texto en columnas (delimitado por coma).
- Normalización de nombres de columnas.
-Conversión de tipos de datos (fechas, números, texto).
-Eliminación de duplicados por OrderID.
-Revisión y estandarización de valores faltantes.
-Creación de columnas auxiliares:
--Año → =AÑO([@Fecha])
--Mes → =TEXTO([@Fecha];"mmmm")
Conversión de la base en Tabla de Excel para facilitar su uso en Tablas Dinámicas (<a href="https://github.com/al3xiss20/Data-Analysis-Dashboard/blob/main/2.png">Nueva Base</a>) .

 ## Dashboard 
<img width="1897" height="761" alt="Dashboard" src="https://github.com/user-attachments/assets/6f1f8387-3fe0-474e-9092-af433ef232a4" />



📊 KPIs Definidos
1.	Ventas Totales
- Etiqueta: Ventas
- Métrica: Suma de Total
- Insight: Muestra el nivel total de ingresos generados. Permite identificar el volumen global de ventas y analizar su evolución en el tiempo.
________________________________________
2.	Número de Transacciones
- Etiqueta: Transacciones
- Métrica: Conteo de OrderID
- Insight: Refleja la cantidad de compras realizadas. Ayuda a evaluar el flujo de clientes y el dinamismo del negocio en distintos períodos.
________________________________________
3.	Rating Promedio
- Etiqueta: Satisfacción
- Métrica: Promedio de Rating
- Insight: Indica el nivel de satisfacción general de los clientes. Detecta fortalezas o posibles áreas de mejora en la experiencia de compra.
________________________________________
4.	Tipo de Cliente
- Etiqueta: Segmento Cliente
- Métrica: Ventas y participación (%) por CustomerType
- Insight: Permite identificar qué grupo (Miembros o Normales) aporta más ingresos y definir estrategias de fidelización.
________________________________________
5.	Método de Pago
- Etiqueta: Medios de Pago
- Métrica: Ventas por categoría de Payment
- Insight: Identifica los métodos más usados. Puede orientar decisiones sobre alianzas bancarias o promociones específicas.
________________________________________
6.	Diferencial de Precio a lo Largo del Tiempo
- Etiqueta: Precio Promedio
- Métrica: Promedio de UnitPrice por período
- Insight: Muestra la evolución de precios, útil para detectar variaciones estacionales o ajustes de estrategia comercial.
________________________________________
7.	Ventas de Productos
- Etiqueta: Productos más vendidos
- Métrica: Ventas por ProductLine (Top 10)
- Insight: Destaca las categorías que concentran mayores ingresos, permitiendo identificar el efecto 80/20 y priorizar inventario.
________________________________________
8.	Filtros de Segmentación
- Etiqueta: Filtros dinámicos
- Métrica: Mes, Año, Género, Sucursal y Ciudad
- Insight: Permiten un análisis detallado, comparando ventas entre períodos, ubicaciones y perfiles de clientes.
