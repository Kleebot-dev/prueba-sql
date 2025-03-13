# prueba-sql

## Instrucciones:
- Basado en la base de datos de los archivos **"schema.sql"** y **"seeder.sql"**, generar una consulta en **SQL (PostgreSQL)**.
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
