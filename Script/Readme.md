Scripts

Código SQL de las tablas se caracterizan con un guion bajo desdpues se indica la accion a describir en cada uno de los scrpts en este caso crear tabla (_create).

Para la creación de las tablas tener en cuenta lo siguiente:

1. Data Lake Nombre dado a la Base de datos.
2. dbo significa propietario de la base de datos (Database Owner).
3. dl significa Data Lake se indica el dl con el fin de identificar los tipos de datos que se tienen.
4. _Departamentos, _Municipios, _Homicidios  nombre dado a la tabla creada.
5. _Create tipo de script a mostrar  

Para el nombre de los archivos se tiene en cuenta los siguiente:

Camel case es un estilo de escritura que consiste en la unión de dos o más palabras sin espacios, donde cada nueva palabra comienza con una letra mayúscula, excepto la primera

dl_Departamentos_Create: CREATE TABLE estructura de la tabla de Departamentos. 

dl_Municipios_Create : CREATE TABLE estructura de la tabla de Municipios. 

dl_Homicidios_Create : CREATE TABLE estructura de la tabla de Homicidios. 
