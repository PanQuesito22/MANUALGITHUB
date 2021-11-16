*Una vez tengamos instaladas dichas aplicacions crearemos una base de datos y un*
*usuario en MySQL para ello entraremos a mysql con el comando "mysql"*

![](mysql.png)

*y pondremos el siguiente comando "mysql -u root" con esto crearemos*
![](root.png)
*entraremos dentro del mysql y podremos modificar las cosas ahi*

*Y ahora crearemos la base de datos con el siguiente comando*
*"CREATE DATABASE ELNOMBREQUETUQUIERAS;"*
![](next.png) *y ahora crearemos un usuario con el que accederemos a la base de datos*

*"CREATE USER 'elmeuusuari'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';"*
![](user.png)
*Usaremos el comando "GRANT ALL ON bbdd. to 'usuario'@'localhost'para darle permisos al usuario*
![](gran2.png)
*Le daremos privilegios de usuario para que se pueda conectar una persona externamente*
*"GRANT ALL ON bbdd. *to 'usuario'@'192.168.22.100';"*
![](all.png)
*Ahora haremos exit para salir de este perfil que hemos creado con nuestra base*
*de datos y procederemos a poner el siguiente comando para comprobar si todo*
*funciona correctamente "mysql -u elmeuusuari -p"*
![ho](nexcloudconfigurado.png)
![ho](nexclouddentro.png)
