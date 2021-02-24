# TEMÓN
Temón es el Trabajo final de la tecnicatura, consiste en una aplicación de streaming de música pensada para personas que sufren de baja visión.  


### Elementos necesarios para la app
* Instalar Node.js
* Instalar React-Native
* Un celular Android 
* Instalar Android studio


### Como Instalar el entorno
* [Guia para instalar el entorno React Native](https://reactnative.dev/docs/environment-setup)


### Tecnologías en la aplicación móvil
* [React Native] (https://reactnative.dev/) 
* [Node.Js] (https://nodejs.org/es/) 


### Pasos para probar la app
* primero: entre en las carpetas temon y temon-backend e instalar las dependencias con el comando "npm install"
* segundo: dentro de la carpeta temon-backend ejecute en la consola "node app.js"
* tercero: dentro de la carpeta temon hay que crear un archivo llamado PersonalConfig.js y pegar el siguiente contenido, pero hay que agregar la dirección ip    
  export const PersonalConfig = {
      url: "Direction IP:8080"
  };
* cuarto: activar el modo desarrollador de tu celular  
* quinto: conectar tu teléfono con un pendrive y verificar si está bien conectado con el comando “adb devices”
* sexto: escribir en la consola el comando "react-native run-android", estando sobre la carpeta temon
