# TareasSeguridadInfo
Aquí voy a incluir las tareas de la asignatura
Barrueta Guzmán José Eduardo 
grupo 2061
319091894
profesor Daniel Fernando Palma López

NOSQL injection

para esta aplicación se debe guardar todos los contenidos de la carpeta NoSQL injection
usar el comando en terminal
node server.js

ahora funciona la página y podemos acceder a ella desde nuestro host local en el puerto 3000 por defecto

con thunder client ponemos esta dirección en el modo POST
http://localhost:3000/login

y este comando JSON en el body

{"user": {"$ne": 1}, "password": {"$ne": 1}}


eso debería darnos una contraseña y un usuario, puede ser user o username 

dependiendo de la carpeta a la que estemos accediendo desde nuestro código main.js podemos obtener diferentes datos de inicio de sesión
en mi caso entré a la carpeta 
users 
de la otra carpeta llamada
nosql_vuln_db 

sólo queda copiar y pegar el usuario y contraseña para acceder
