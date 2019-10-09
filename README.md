# API-RESTfull-Instagram
creación de una api para gestionar cuentas de instagram

#Es necesario registrarse en la api de instagram como desarrollador
https://www.instagram.com/developer/ 

#Luego de estar registrado en la api de instagram, debemos en Manage Clients registrarnos
#Colocar nuestro url (localhost:xxxx) y la información correspondiente 

#Instagran nos dará  dos claves, tanto el id como la clave secreta
Client ID xxxxxxxxxxxxxxxxxxxxxxxx
Client Secret xxxxxxxxxxxxxxxxxxxx
#Estas claves nos permiten autenticarnos 

# Para instalar los modulos que requerimos 
npm install node
# Se descargarán las dependencias tanto de desarrollo como modulos utilizados en el proyecto 
# express, nodemon, node-instagram, body-parser, morgan 

#Una vez instalamos los modulos necesarios podemos correr la aplicación
#Para correr la api desde consola es: -> npm run dev

###########################################################################################
# Modulo de node-instagram  utilizado en el proyecto

#node-instagram
https://www.npmjs.com/package/node-instagram
Instagram api client for node that support promises and typescript.

Install
npm install --save node-instagram
yarn add node-instagram

# Api restfull pasos 
1) Loguearnos 
2) Autenticarnos 
3) Endpoints 

#La Api nos permite mirar las últimas 20 publicaciones más recientes del perfil de usuario
#Obtener la cantidad de seguidores, de personas que nos siguen y los likes que tenemos en esas 20 publicaciones
#Para obtener la eficiencia es número de likes / el número de seguidores







