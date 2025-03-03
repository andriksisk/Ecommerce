# Creación de las tablas en bases de datos

Al momento de crear la base de datos tuvimos en cuenta varios puntos, ya que, para ir ingresando los datos en MySQL, debían ya estar formalizados y con una cierta regla para que no haya algún conflicto y los datos sean los correctos

> Diseño de tablas

* Nombre de la tabla: Usar nombres significativos y comprensibles
* Nombre de columnas: Que sean descriptivos y claros
* Definir bien los índices 
* Claves primarias: Definiar alguna columna como clave primaria para identificar de manera única cada fila de la tabla
* Claves foráneas: Nos ayuda para mantener las relaciones entre algunas tablas 

> Al ingresar datos

* Comprobar que los tipos de datos sean los correctos
* Valores NULL: Tomar en cuenta qué tipos de datos van a tener como tipo NULL
* Manejo de valores duplicados: Tenemos que hacer uso de la "función" UNIQUE" para evitar que no haya datos duplicados

## Creacion en nuestro proyecto 

Creamos varias tablas (12 en total), en cada una le agregamos diferentes tipos de valores, como INT, DATE, VARCHAR, TIME, entre otras más. Todos estos elementos previos los sacamos de los modelos entidad relación.  

> La estructura base para la creación de estas tablas es "CREATE TABLE -NOMBRE- (-INGRESAR LOS ELEMENTOS DESEADOS-)



