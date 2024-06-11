# HeroesApp
Esta aplicación puede ser vista en esta [Github page](https://will-h0219.github.io/heroesApp)

Nota: En API se encuentra desplegado en RENDER por lo que puede ser necesario intentar dar click a "Ingresar" o "Ingresar sin login" más de una vez.

## English

This project was made from scratch with Angular, this app allows the user to see all the heroes stored in a database, search for a specific heroe (it only returns the data of the heroe in a json format) and create heroes that are missing in the list showed before. Some features in the app is the use of lazy load for different components, also the implementation of [Angular Material](https://material.angular.io) for the style of almost everything that you see in the app.

### To visualize

To correctly visualize the correcto operation of the app, it's necessary to use [JSON Server](https://www.npmjs.com/package/json-server), just do the install process al run the start command ```json-server --watch db.json``` inside the folder HEROES-SERVER.

## Español

Este proyecto fue hecho desde cero con Angular, esta aplicación permite al usuario ver todos los heroes guardados en una base de datos, buscar por un heroe en especifico (la aplicación devolvera la información del heroe en formato JSON) y crear a los heroes que hagan falta en la lista mostrada. Algunas funcionalidades presentes en la aplicación es el uso de lazy load o carga perezosa paraalgunos componentes, tambien se utilizo [Angular Material](https://material.angular.io) para el estilo de la mayor parte de componentes de la aplicación.

### Para visualizar

Para visualizar correctamente el funcionamiento de la app es necesario usar [JSON Server](https://www.npmjs.com/package/json-server), realizar la instalación de la página y correr el comando de inicialización del servidor ```json-server --watch db.json``` dentro de la carpeta HEROES-SERVER.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
