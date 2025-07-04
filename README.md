# Análisis de ventas con Power BI

Este proyecto presenta un análisis de datos de ventas utilizando Power BI, aplicando un proceso de ETL con Power Query 
y visualización de indicadores clave(KPIs) para la toma de decisiones.

# Descripción del dataset

El dataset contiene transacciones detalladas de ventas, incluyendo:
- Información de pedidos
- Ingresos
- Ganancia
- Datos de clientes
- Categorías
- Fechas
- Ubicaciones

# Fuente

- (Kaggle - Sales Dataset) https://www.kaggle.com/datasets/shantanugarg274/sales-dataset?resource=download

# Proceso del trabajo

1. Carga del archivo CSV en Power BI.
2. Limpieza y transformación de datos (ETL) usando Power Query.
3. Creación de una tabla calendario a partir del mínimo y máximo de fechas.
4. Modelado de relaciones entre tablas para análisis cruzado.
5. Construcción de medidas con DAX para los KPIs.
6. Diseño de visualizaciones dinámicas y limpias con énfasis en la usabilidad.
7. Implementación de "tooltips inteligentes" para mostrar información adicional sin saturar la vista principal.
8. Creación de marcadores (bookmarks) para alternar entre vistas basadas en ventas y unidades.


# KPIs y visualizaciones principales

- Total de ventas
- Ganancia
- Variación porcentual respecto al año anterior
- Número de clientes únicos
- Ticket promedio 
- Unidades vendidas
- Margen de ganancia por estado
- Ranking de categorías y subcategorías
- Ventas por método de pago
- Mapa de ventas por ciudad

# Funcionalidades destacadas 

* Tooltips avanzados:
  - Al pasar el cursor sobre el nombre de un estado, se muestra una tabla con las ciudades con sus unidades vendidas     y sus ventas correspondientes.
  - Al pasar sobre una categoría, se activa un gráfico de anillos con el desglose por subcategoría.
* Interacción con marcadores:
  - Un botón permite cambiar la vista principal del dashboard entre:
    - Ventas
    - Unidades vendidas
  - Esto permite al usuario analizar tanto el ingreso monetario como el volumen físico, de forma independiente y sin     saturar visuales.

# Herramientas utilizadas

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)

# Autor 

Bryan Steven De la cruz Cayao 
Estudiante de Ingeniería de Sistemas computacionales

**PROYECTO REALIZADO CON FINES DE APRENDIZAJE Y PORTAFOLIO**

  
