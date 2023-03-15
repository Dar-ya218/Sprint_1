
S1. HTML y CSS;

Ten en cuenta las siguientes consideraciones. Son errores habituales en las entregas:

En general, nunca le ponemos height a una capa, sino que dejamos que la capa se adapte a su contenido (si la capa no tiene contenido, le puedes poner un height).
La página no debería tener barra de scroll horizontal (si te pasa, tendrás que averiguar inspeccionando la página qué bloque es más ancho que la pantalla del navegador).
Dentro de un div suele haber otros divs. Los divs tienen display:block por defecto. Esto hace que se vayan colocando de manera vertical. Por lo tanto, a menudo no es necesario especificar los siguientes estilos para un elemento para ser algo redundante:
.element{ display:flex; flex-direction:column }
En un div, por defecto el ancho es la totalidad de la capa que envuelve, así que normalmente no será necesario especificar width:100%

Entrega por GitHub

- Crea un único repositorio de GitHub para los tres niveles, los podrás separar en carpetas.
Por ejemplo: nivel-1, nivel-2 y nivel-3.

- En los dos primeros sprints tendrás que subir el código a GitHub para que pueda verlo tu mentor/a.A
partir del sprint 3 tendrás que entregarlo vía pull request, tal como se hace en una empresa.