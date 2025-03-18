Sorteo de Amigos

Este proyecto es una aplicación sencilla desarrollada en JavaScript para realizar un sorteo de amigos de manera aleatoria. Permite agregar amigos a una lista y luego sortear a uno de ellos.

Archivos del Proyecto

index.html
Contiene la estructura HTML de la aplicación, incluyendo los campos de entrada, botones y la lista donde se muestran los amigos.

styles.css
Define los estilos visuales de la aplicación para mejorar la presentación de la interfaz.

script.js
Contiene la lógica principal del sorteo. Sus funciones principales incluyen:

asignarElementoTexto: Asigna texto a un elemento HTML dado.

añadirAmigo: Agrega un amigo a la lista, validando que el campo no esté vacío y que el nombre no esté repetido.

sortearAmigo: Selecciona un amigo al azar de la lista y lo muestra en pantalla.

actualizarListaAmigos: Actualiza la lista de amigos en la interfaz.

Bibliotecas Utilizadas

Este proyecto usa JavaScript puro sin dependencias adicionales.

Ejecución de la Aplicación

Para ejecutar la aplicación, simplemente abre el archivo index.html en un navegador web compatible.

Uso

Escribe el nombre de un amigo en el campo de entrada.

Presiona el botón "Agregar" para añadirlo a la lista.

Una vez agregados los amigos, presiona "Sortear" para elegir un amigo al azar.

El amigo seleccionado se mostrará en pantalla y se eliminará de la lista.

Notas:

Si intentas agregar un nombre vacío, recibirás un mensaje de advertencia.

No se pueden agregar amigos duplicados.

Si la lista está vacía, el sorteo no se ejecutará.