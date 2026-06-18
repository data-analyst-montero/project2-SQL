#project2-SQL
Lógica: Consultas de SQL

### 1.🎬 Proyecto SQL - Consultas sobre la Base de Datos de un video club
El objetivo principal es poner en práctica los conocimientos de SQL para el análisis de datos almacenados en múltiples tablas y la generación de métricas relevantes para la toma de decisiones.

### 2. 📖 Descripción del Proyecto
Este proyecto consiste en la realización de consultas SQL sobre una base de datos de ejemplo, utilizando PostgreSQL y DBeaver como entorno de trabajo de una base de datos real de gestión de alquileres de películas.

El proyecto aborda diferentes necesidades de análisis de negocio, como la identificación de clientes más activos, el estudio de patrones de alquiler, el análisis de categorías de películas, la obtención de estadísticas de ingresos y la exploración de relaciones entre actores, películas y clientes. De esta forma, se demuestra cómo una base de datos relacional puede utilizarse para extraer conocimiento útil a partir de grandes volúmenes de información.

#### Para llevar a cabo el proyecto se han empleado diversas técnicas y enfoques de consulta SQL:
*	Consultas de selección y filtrado de datos mediante SELECT, WHERE, ORDER BY y LIMIT. 
*	Uso de funciones de agregación como COUNT, SUM, AVG, MIN, MAX, STDDEV y VARIANCE. 
*	Relación de tablas mediante INNER JOIN, LEFT JOIN y CROSS JOIN. 
*	Implementación de subconsultas para resolver problemas de análisis más complejos. 
*	Agrupación y filtrado de resultados con GROUP BY y HAVING. 
*	Creación de vistas (VIEW) para reutilizar consultas frecuentes.
*	Uso de tablas temporales para almacenar resultados intermedios. 
*	Aplicación de funciones de fecha y operaciones estadísticas para el análisis de alquileres y pagos. 
Gracias a este conjunto de ejercicios, el proyecto permite adquirir experiencia práctica en el manejo de bases de datos relacionales, reforzando conceptos clave de SQL y desarrollando habilidades esenciales para tareas de análisis de datos y administración de bases de datos.

### 3. 🗂️ Estructura del Proyecto
```
├── docs/ 
│    └── EnunciadoDataProject_SQL_Logica.pdf
│    └── Esquema de la BBDD.pdf
├── BBDD_Proyecto_shakila_sinuser.sql
├── consultas.sql
├── README.md 
```

### 4. ⚙️ Instalación y Requisitos
#### Para ejecutar este proyecto es necesario instalar:
*	PostgreSQL 14
*	DBeaver
*	Base de datos Sakila para PostgreSQL
  
#### Pasos de instalación
1.	Crear una base de datos nueva en PostgreSQL.
CREATE DATABASE sakila;
2.	Abrir DBeaver y conectarse a la base de datos creada.
3.	Ejecutar el script:
BBDD_Proyecto_shakila_sinuser.sql
4.	Verificar que las tablas se han creado correctamente.
5.	Ejecutar las consultas contenidas en el archivo de resolución.

### 5.	📊 Resultados y Conclusiones
A través de las consultas desarrolladas se han obtenido métricas relacionadas con el comportamiento de los clientes, el rendimiento del catálogo de películas, los ingresos generados por la empresa y la distribución de los alquileres por categorías. Asimismo, se han identificado patrones de uso y relaciones entre las distintas entidades de la base de datos, como clientes, actores, películas, categorías y alquileres.

Los resultados obtenidos ponen de manifiesto la importancia de las bases de datos relacionales como herramienta para el almacenamiento y explotación de información empresarial. Mediante el uso de consultas SQL es posible responder a preguntas de negocio de forma rápida y precisa, proporcionando información valiosa para optimizar la gestión de clientes, mejorar la planificación del catálogo y evaluar el rendimiento general de la actividad comercial.

En conclusión, este proyecto ha permitido consolidar los conocimientos sobre consultas SQL y gestión de bases de datos relacionales, demostrando cómo las técnicas de filtrado, agregación, relaciones entre tablas, subconsultas y vistas pueden utilizarse para extraer información estratégica a partir de datos operativos.

### 6. 🤝 Contribuciones
#### Las contribuciones y mejoras son bienvenidas.
Si deseas ampliar el conjunto de consultas o proponer nuevas soluciones, puedes hacerlo mediante:
*	Creación de nuevas consultas SQL.
*	Optimización de consultas existentes.

### 7. 👩🏻‍💻 Autor
Giselle Montero González (https://github.com/data-analyst-montero)

### 8. 🙏 Agradecimientos
* A los instructores de ThePower por sus materiales formativos utilizados durante el desarrollo de la práctica.
