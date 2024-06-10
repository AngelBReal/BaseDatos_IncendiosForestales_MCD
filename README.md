# BaseDatos_IncendiosForestales_MCD
## Configuración de la base de datos

Instrucciones para configurar la base de datos.

1. Instala [MySQL/PostgreSQL/etc.]
2. Crea una base de datos llamada `nombre_de_la_base_de_datos`.
3. Ejecuta los siguientes comandos SQL para configurar las tablas:

```sql
-- Ejemplo de comando SQL
CREATE TABLE ejemplo (
    id INT PRIMARY KEY,
    nombre VARCHAR(100)
);
