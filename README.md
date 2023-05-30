# Buscador de cócteles.

Este proyecto consiste en desarrollar una aplicación web que contiene un listado de las bebidas y cócteles de todo el mundo, que nos permite hacer búsquedas y también seleccionar las bebidas como favoritas y guardarlas en local storage.

## Herramientas:

He utilizado una plantilla de proyecto creada con node y gulp, que incluye:

- Un motor de plantillas HTML.
- Preprocesador SASS.
- Servidor local.
- Otras funcionalidades preinstaladas y preconfiguradas.

#### Lenguaje utilizado:

Javascript, dentro del cual he utilizando:

- DOM avanzado.
- Eventos.
- Fetch. Llamada a la API (https://www.thecocktaildb.com/).
- LocalStorage.
- Métodos de arrays.
- Objetos.

## Estructura básica del ejercicio:

La aplicación de búsqueda de cócteles consta de tres partes:

- Un campo de texto y un botón para buscar un cóctel por su título.
- Un listado de resultados de búsqueda donde aparece la imagen del cóctel y el nombre.
- Apartado de favoritos

#### Features:

- Al hacer click sobre el icono de una 'x' al lado de cada favorito, se borra el favorito clicado de la lista y también del localStorage.
- Podemos añadir/quitar como favorito al hacer clic sobre un cóctel del listado de favoritos.
- Si realizamos una nueva búsqueda y sale un cóctel que ya es favorito, aparece ya resaltado en los resultados de búsqueda.
- Al final de la lista de favoritos hay un botón para borrar todos los favoritos a la vez.

##### ©Adalab

![Mojitos](https://www.shutterstock.com/image-vector/cocktails-word-concept-flat-vector-260nw-1730830228.jpg)
