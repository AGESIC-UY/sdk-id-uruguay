# PIS2020

## Metodología de desarrollo

### Instalación del proyecto

Para instalar el proyecto por primera vez se debe de instalar la branch `develop` y luego ejecutar el comando `npm install`.

Cada vez que se agregue una nueva librería o dependencias, se deberá ejecutar el comando `npm install` antes de poder levantar el proyecto.

### Iniciar el proyecto

Para iniciar el proyecto se debe ejecutar el comando `npm start`.

Una vez hecho esto, se abrirá una ventana del navegador con el metro bundler corriendo. El siguiente paso es escanear el código QR en sus celulares
... el cual les abrirá la app de Expo (Deben instalarla previamente).ç
La otra opción es, luego de levantado el proyecto, ejecutar `i` para simulador iOS o `a` para Android.

### Sistema de branches y PRs

Al comenzar a trabajar en una feature, se deberá crear una nueva branch desde la branch `develop` con el nombre `feature/nombre-de-la-feature`.
Si se está arreglando un error o bug, la branch deberá llamarse `bugfix/nombre-del-bugfix`.

Una vez finalizado el trabajo en una feature (o bugfix), se deberá crear un Pull Request (PR) a la branch `develop`. Una vez creado el PR, un miembro del Comité .... deberá revisarlo y aprobarlo (o pedirle al desarrollador que se realicen cambios). <b>Solo una vez aprobado el PR es que se debe hacer el merge a `develop`</b>.

La branch `master` está reservada únicamente para releases.
