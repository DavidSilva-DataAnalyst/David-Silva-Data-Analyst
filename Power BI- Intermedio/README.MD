# Venta de Cliente por Departamento — Dashboard Interactivo en Power BI

## Objetivo

Dashboard interactivo diseñado para analizar el comportamiento de ventas por cliente, país, ciudad y curso, permitiendo a los usuarios explorar los datos de forma dinámica mediante filtros y segmentaciones que se ajustan en tiempo real en todas las visualizaciones.

## Datos

El dashboard está conectado a una base de datos en Excel. Cualquier modificación o dato nuevo agregado en el archivo origen alimenta automáticamente el dashboard, sin necesidad de reconstruir las visualizaciones manualmente.

## Qué hice

* **Conexión dinámica a Excel**: el modelo se actualiza automáticamente al modificar o agregar registros en la base de datos origen.
* **Segmentación de datos (slicers)**: filtros interactivos por país, ciudad y cliente que actualizan todas las gráficas y KPIs del dashboard simultáneamente.
* **Visualizaciones aplicadas**:

  * Velocímetro (gauge) para nivel de ventas
  * Tarjetas KPI (importe cliente, duración)
  * Mapas coropléticos (importe por país)
  * Mapas segmentados con burbujas (importe por ciudad, duración por ciudad y jornada de curso)
  * Tabla interactiva de detalle por cliente
* **Interactividad cruzada**: al seleccionar un país, ciudad o cliente, todas las visualizaciones del reporte se ajustan automáticamente reflejando el subconjunto de datos filtrado.

## Resultado

&#x20;      !\[Dashboard sin filtros activados](./Capturas/Dashboard-sin-Filtros-Activados.png) 

&#x20;      !\[Dashboard con un filtro activado](./Capturas/Dashboard-Un-Filtro-Activado.png)

&#x20;      !\[Dashboard con varios filtros activados](./Capturas/Dashboard-Varios-Filtros-Activados.png)

## Insights principales

* Identificación de los clientes con mayor importe de venta (Cliente-005 y Cliente-003 concentran los montos más altos).
* Visualización clara de la distribución geográfica de clientes entre España, Francia e Italia.
* Análisis de duración de cursos segmentado por jornada (mañana, tarde, noche) y ciudad, útil para planificación operativa.

