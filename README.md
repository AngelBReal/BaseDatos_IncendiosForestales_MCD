# BaseDatos_IncendiosForestales_MCD
# Incendios Forestales Data

This repository contains data on forest fires from 2015 to 2023.

# Proyecto Bases de Datos

## Descripción
Este proyecto lee datos de una base de datos MySQL local y realiza un análisis de datos sobre incidentes de incendios forestales desde 2015 hasta 2023.

## Requisitos
- Python 3.x
- Servidor MySQL

## Instrucciones de Configuración

### 1. Clonar el Repositorio
Primero, clona el repositorio a tu máquina local:
```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
```
### 2. Instalar Paquetes de Python
Instala los paquetes de Python necesarios usando requirements.txt:

```bash
pip install -r requirements.txt
```
### 3. Configurar la Base de Datos MySQL
#### a. Actualizar la Ruta del Archivo CSV
Abre el archivo mysql_code.txt y actualiza la ruta a tu archivo CSV en el comando LOAD DATA INFILE.

#### b. Ejecutar el Script de Configuración de la Base de Datos
Ejecuta los codigos en el archivo en los querys de MySQL. Asegúrate de que MySQL esté ejecutándose y sea accesible:

### 4. Ejecutar el Jupyter Notebook
Inicia Jupyter Notebook y abre el notebook del proyecto:

```bash
jupyter notebook notebooks/Proyecto Bases de Datos.ipynb
```
Sigue las instrucciones dentro del notebook para realizar el análisis de datos.

### Descripción de los Archivos
data/csv_db_incendios_forestales.csv: El conjunto de datos utilizado en este proyecto.
mysql_code.txt: Código SQL para crear la base de datos y cargar los datos.
notebooks/Proyecto Bases de Datos.ipynb: Jupyter Notebook con el análisis de datos.
requirements.txt: Lista de paquetes de Python requeridos.

### Resolución de Problemas
Problemas de Conexión a la Base de Datos: Asegúrate de que MySQL esté ejecutándose y que los detalles de conexión en los scripts coincidan con tu configuración de MySQL.
Ruta del Archivo CSV: Verifica que la ruta al archivo CSV en mysql_code.txt sea correcta.
Dependencias: Asegúrate de que todas las dependencias estén instaladas a través de requirements.txt.

### Notas Adicionales
Asegúrate de que el archivo CSV utilice el delimitador correcto (;) y esté correctamente formateado.
