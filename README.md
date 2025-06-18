# paginaweb
La idea era que podamos cargar datos de personas (como el nombre, apellido y edad) y después verlos en una tabla. Para eso usé un programa llamado XAMPP, que te deja tener un servidor web en tu propia compu.

Primero instalé XAMPP y lo abrí. Está buenísimo porque ya viene con todo junto: Apache, que es el servidor; MySQL, que es donde se guardan los datos; y PHP, que es el lenguaje con el que programé todo. Solo tuve que prender Apache y MySQL desde el panel y ya estaba listo para empezar.

Después entré a phpMyAdmin, que es una página que te deja crear y manejar bases de datos fácil. Ahí armé una base que se llama "escuelaa" y dentro hice una tabla llamada "personas". A esa tabla le puse cuatro columnas: una para el id (que se genera solo) y otras tres para el nombre, apellido y edad.

Cuando terminé eso, pasé a hacer el código en PHP. Hice un formulario donde podés cargar los datos de una persona y, cuando apretás enviar, el PHP los guarda en la base de datos. También hice que se vean todos los registros en una tabla más abajo, así podés ver a quiénes agregaste.

Para que todo se vea más lindo y no tan básico, usé Bootstrap, que ayuda un montón con el diseño. Al final, la app quedó funcionando re bien, podés agregar personas, verlas en la lista, y si algo falla, te avisa.
