# csv_mysql
Procedimiento para pasar de CSV a Mysql

# Pasos:
* Importar los archivos CSV a la Base de Datos ( con cualquier herramienta que conoces)
* Adapta el SQL dependiendo de lo que necesitas:
```
SELECT matriz.*, a.*
FROM organiz a
join matriz on matriz.name=a.name
order by 
a.name asc
```
