# Requisitos

## [1] Creación de cuenta y autenticación.

- El usuario tiene que poder registrarse
  - Usando su email y contraseña.
  - Usando su cuenta de google o facebook.
- El usuario tiene que poder iniciar sesión usando su email y contraseña.
- El usuario tiene que poder iniciar sesión usando su cuenta de google o facebook.
- El usuario tiene que poder recuperar su contraseña en caso de que se haya registrado usando su email y contraseña.
- El usuario tiene que poder escoger su nombre de usuario único y subir su imagen de perfil.

## [2] Creación de una conversación

- El usuario tiene que poder ver un listado de usuarios con los que poder interactuar.
- El usuario tiene que poder enviar una petición de conversación a otro usuario.
  - Descripción
    - La petición de conversación debe tener un mensaje corto (300 caracteres)
- El usuario tiene que poder ver un listado de peticiones de conversación con su respectivo mensaje.
    - El usuario tiene que poder aceptar o rechazar las peticiones de conversación.
      - Descripción
        - Si el usuario acepta la petición, se deberá crear una conversación.
        - Si el usuario rechaza la petición, desaparecerá del listado.
  - Descripción    
    - Si el usuario (A) ha bloqueado anteriormente al usuario (B) que ha enviado la petición de conversación, esta petición de conversación no será visible en el listado.

## [3] Listado de conversaciones

- El usuario tiene que poder ver un listado de conversaciones
- El usuario tiene que poder buscar entre las conversaciones creadas por el nombre del usuario

## [4] Envío de mensajes dentro de una conversación

- El usuario tiene que poder enviar mensajes de texto
- El usuario tiene que poder enviar mensajes de audio
- El usuario tiene que poder enviar imagenes desde su ordenador
- El usuario tiene que poder enviar imagenes desde su cámara
- El usuario tiene que poder enviar videos desde su ordenador
- El usuario tiene que poder enviar videos desde su cámara

## [5] Lectura de los mensajes dentro de una conversación

- El usuario tiene que poder hacer scroll hacia arriba para ver los mensajes anteriores.
- El usuario tiene que poder ver la fecha en la que se envió un grupo de mensajes. 
  - Descripción
    - Agrupados por dia, a partir de hoy al hacer scroll hacia arriba.
- El usuario siempre tiene que poder ver la hora en la que se envió el mensaje.
- El usuario tiene que poder diferenciar visualmente sus mensajes respecto a los del resto de usuarios.
- El usuario tiene que poder buscar los mensajes por texto.

## [6] Acciones sobre los mensajes

- El usuario tiene que poder eliminar un mensaje.
  - Descripción
    - La eliminación del mensaje será efectiva para todos los usuarios.
- El usuario tiene que poder editar un mensaje. 
  - Descripción
    - En caso de edición de un mensaje, se representará visualmente que ese mensaje ha sido editado.
- El usuario tiene que poder responder a un mensaje en concreto.
- El usuario tiene que poder reenviar un mensaje.

## [7] Estados del usuario

- El usuario tiene que poder saber si los otros usuarios están online
- El usuario tiene que poder cambiar su estado a "No Disponible"

## [8] Notificaciones

- El usuario tiene que recibir notificaciones de escritorio cuando alguien le envie un mensaje.
- El usuario tiene que poder desactivar las notificaciones de escritorio.

## Pantallas

* [1] Creación de cuenta
* [1] Inicio de sesión
* [1] Recuperar contraseña
* [1] Revisar email
* [1] Nueva Contraseña
* Chat
  * [3] Listado de Conversaciones a la izquierda
    * [2] Botón "Crear Conversación". Abre un modal y muestra a los usuarios registrados en la aplicación
  * [4, 5, 6] Conversación activa a la derecha
* [7,8] Perfil