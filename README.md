# Argentina-Provincias-localidades
Tablas necesarias para tener las provincias, localidades, departamentos y municipios de Argentina
Los datos fueron tomados del sitio https://datos.gob.ar/

Todos los scripts se encuentran en el directorio SQL.
Para tener la estructura completa, se deben correr los siguientes scripts : 

1. Provincias.sql
2. Departamentos.sql
3. Municipios.sql
4. Localidades.sql

> Se deben corren en ese

![image](https://github.com/lcassettai/Argentina-Provincias-localidades/assets/12787110/d8c00ad3-70ec-47d6-a1fd-d59b99d1e393)

En caso de querer tener solo las provincias con localides se debe correr los siguientes scripts: 

1. Provincias.sql
2. Localidades - SIN Municipios y Departamenos.sql

![image](https://github.com/lcassettai/Argentina-Provincias-localidades/assets/12787110/5fde2ef0-dc91-47da-a6b8-da0e957723fa)


> Los scripts fueron creados a partir de los CSV descargados del sitio https://datos.gob.ar/, y luego fueron creados utilizando el siguiente sitio https://www.convertcsv.com/csv-to-sql.htm

> Unicamente fueron probados en una base de datos PostgreSQL pero deberia funcionar bien en MySQL

Si encontras algun error y queres contribuir realizá un Merge Request y vamos mejorando el script.
