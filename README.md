# add_emails
Anotador de emails
App que agrega y elimina emails <br>
Agregar y almacenar usuarios: La aplicación permite a los usuarios ingresar su nombre y dirección de correo electrónico en los campos correspondientes. Al hacer clic en el botón "Agregar", se valida la dirección de correo electrónico y se crea un nuevo usuario con un ID único. Luego, el usuario se agrega a una lista de usuarios que se almacena en el almacenamiento local del navegador utilizando localStorage. <br> <br>

Visualizar y editar usuarios: La aplicación muestra una tabla que enumera todos los usuarios registrados. Cada fila de la tabla muestra el ID, nombre y correo electrónico del usuario, junto con opciones para editar o eliminar el usuario. Al hacer clic en el botón "Editar" de un usuario específico, se muestra un formulario de actualización con los campos de nombre y correo electrónico prellenados con los valores actuales del usuario. Los cambios realizados se guardan en el arreglo de usuarios y se actualiza la tabla. <br> <br>

Eliminar usuarios: Junto a cada usuario en la tabla, hay un botón "Eliminar" que permite eliminar el usuario correspondiente de la lista. Al hacer clic en este botón, se elimina el usuario del arreglo de usuarios y se actualiza la tabla. Si no quedan usuarios en la lista, el formulario de actualización se oculta. Los cambios se guardan en localStorage para persistencia de datos. <br> <br>
<img src="./front.png">