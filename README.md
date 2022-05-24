# Punto-de-venta-para-electronica
Este sistema representa un punto de venta con los elementos más básicos que se administran en una tienda electrónica.
Primeramente, se descarga el archivo .sql (electronica(2).sql) y luego se importa desde el SGBD MySQL, para ello, se crea una base de datos denominada electronica y
después de importa el archivo .sql dentro de la base de datos creada (esto hará que las tablas y relaciones creadas se transfieran automáticamente en la base de datos
creada).
Para tener acceso al punto de venta, es preferible tener instalada la última versión de WampServer. Una vez instalada dicha herramienta, es necesario descomprimir la
carpeta del archivo .RAR. Una vez extraída la carpeta es necesario dirigirse dentro de la carpeta de WampServer dentro del disco local C (normalmente se denomina wamp64)
y dentro de dicha carpeta buscan la carpeta www, finalmente, dentro de la carpeta www es donde se colocará la carpeta extraída del archivo .RAR para poder montar el
punto de venta desde el servidor local. Para visualizar el punto de venta, es necesario colocar la siguiente liga: localhost/nombre_de_la_carpeta_extraída_en_la_carpeta_www
