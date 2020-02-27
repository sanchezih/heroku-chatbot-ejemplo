# Simple Chat-Bot on Facebook Messenger usando Node.js

## Requisitos
Node.js
Cuenta en Heroku
Heroku-CLI
Cuenta en Facebook for developers
Git

## Procedimiento
Para crear el Bot lo que necesitamos es comunicar Facebook con el servidor almacenado en Heroku. Usando Send API, este API es el punto de partida para toda la integración porque nos permite enviar texto simple y plantillas estructuradas para mensajes. Por ejemplo, imágenes videos, audio y archivos.
La plataforma de Messenger envía un evento a nuestro webhook cada vez que ocurre una acción en el chat. Webhook es una de las rutas que nos permite capturar estos eventos mediante las solicitudes POST. Es ahí donde usaremos Node.js para recepcionar el evento y programar un Chat Bot para procesar y responder a los eventos.

[Articulo](https://medium.com/cmaquera/crear-un-simple-chat-bot-on-facebook-messenger-usando-node-js-c0ed373bddda)

