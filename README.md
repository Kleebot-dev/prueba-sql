# 1. Reporte de dirección

## Instrucciones:
Basado en la base de datos de los archivos **"schema.sql"** y **"seeder.sql"**, generar una consulta en **SQL (PostgreSQL)**.
- Debe ser una **consulta SQL** que se ejecute en una **sola transacción**.
- Compartir por correo el archivo **"prueba_sql.sql"**.  
  *(Si no se indica un correo, solicitarlo antes de enviar la prueba).*

---

## Columnas a incluir en el reporte:
- **Año:** Año de la transacción.
- **Mes:** Mes de la transacción.
- **Nombre del Cliente**.
- **RFC del Cliente**.
- **Producto:** Nombre del producto vendido.
- **Acumulado Histórico:** Suma total de las ventas históricas hasta la fecha.
- **Acumulado Año Actual:** Total de ventas acumuladas en el año en curso.
- **Acumulado Últimos 2 Meses:** Total de ventas acumuladas en los últimos dos meses.
- **Mismos 2 Meses del Año Pasado:** Total de ventas acumuladas en los mismos dos meses del año anterior.
- **Producto Más Vendido el Año Pasado:** Producto con mayor número de ventas en el año anterior.  
  *(Repetir el mismo valor en todas las filas, aunque la columna "Producto" no coincida).*
- **Desviación Estándar de Venta por Año:** Medida de la variabilidad en las ventas del año en curso.  
  *(Repetir el mismo valor, aunque la resolución más baja sea por meses).*

---

## Ordenamiento de los datos:
1. Primero por **Año** en orden descendente.
2. Luego por **Mes** en orden descendente.
3. Luego por **Nombre del Cliente** en orden ascendente (alfabéticamente).
4. Luego por **Nombre del Producto** en orden ascendente (alfabéticamente).

## 2. Diseño e implementación de tablero en Power BI
1. Diseñar un **tablero en Power BI** que visualice de forma clara y efectiva la información del reporte generado.
2. El tablero debe incluir **al menos cuatro visualizaciones** (gráficos, tablas, indicadores, etc.).
3. El diseño es completamente **libre**, por lo que puedes elegir la distribución, colores y tipos de gráficos que consideres más adecuados para comunicar los datos de manera visual y comprensible.

# 3. Diseño de Base de Datos - Sistema CRM

## Instrucciones:
Investiga qué es un sistema **CRM (Customer Relationship Management)** y cuáles son sus componentes principales.

Con base en tu investigación:

- Diseña un **diagrama entidad-relación** que represente un CRM básico.
- Escribe el **script SQL** para crear la base de datos, incluyendo las tablas necesarias y sus relaciones.

## Requisitos:
- El diseño debe cubrir las entidades mínimas que consideres esenciales para un CRM.
- El entregable debe ser un **archivo .sql** (dump PostgreSQL) con la estructura de la base de datos.
