# Proyecto To Do List
En este proyecto nos enfocamos en realizar una aplicacion de creacion de listas, capaz de editar y borrar las tareas que se crean. Ademas de contener un Login para los usuarios, permitiendoles crear su cuenta y cambiar su contraseña en caso de que se les olvide.

Se planeaba tener la opcion de crear listas de diferentes tareas, como categorias dependiendo de los gustos del usuario de tal forma que este mismo podria editarlas y reacomodarlas.

# Parte Técnica
Se planteo realizar el proyecto con una base de datos de MySQL, utilizando PHP, HTML, Gulp , JS Y SASS.
Utice una extension del composer la cual es PHPMailer, esta extensión ayuda a conectar un servicio para enviar la informacion del correo del usuario, contraseña, e intercambio de informacion.
Aunque en la version gratutita del servicio de correos tiene herramientas utilies, es mejor con la version de paga.

Tambien en cuanto a nuestra bases de datos los password y los datos del usuario estan hasheados, para tener una mejor seguridad tambien estan protegidas las URL, para que en dado caso de querer eliminar una tarea ya sea por que la pagina se quedo con el cache o algo por el estilo, se te pedira siempre hacer login primero antes de cualquier otra modificación

Nuestro login tambien tiene ciertas reglas que cumplir por ejemplo los numeros de caracteres que debe tener la contraseña o el hecho de que no puedas dejar campos vaciós es algo importante para que realmente funcione bien.

# Dificultades en el proyecto
En todo caso hay un problema especifico con esto, lastimosamente a pesar de tener todo nuestro proyecto estructurado, al parecer por un error especifico de PHP o probablemente el Composer el proyecto de funcionar, pero este tambien puede servir en dado caso de querer utilizarse

# Conclusion
Fue un proyecto bastante entretenido, apesar de las dificultades, cualquiera que lo necesite lo puede realizar.

Podemos decir en otras palabras que el proyecto es totalmente funcional y que realmente seria algo util en algun dado caso, siento que podria mejorarse en muchos aspectos como añadir grupos, algo asi como compartir las listas como lo hace Google Drive con su funcion de que varias personas puedan estar modificando el mismo archivo, en fin todavia puede mejorarse mucho.

# Imagenes del Proyecto Antes del Desastre
![image](https://user-images.githubusercontent.com/111943639/205853649-b2fb2a40-9992-4b74-982c-6756f22361f8.png)
![image](https://user-images.githubusercontent.com/111943639/205853709-585dc1c5-cb81-4082-ae9d-89cbe3b918d8.png)
![image](https://user-images.githubusercontent.com/111943639/205853967-acc97f49-33e3-4ce5-b74f-0cde39d6457b.png)
![image](https://user-images.githubusercontent.com/111943639/205854030-f9e5c561-f6ce-469d-a6d6-8f78f7cc4f70.png)
![image](https://user-images.githubusercontent.com/111943639/205854112-3aef2172-99fd-4419-9713-e2abf248f353.png)
![image](https://user-images.githubusercontent.com/111943639/205854194-bec9cc26-9802-49ed-832e-2a6d5d64a83a.png)


