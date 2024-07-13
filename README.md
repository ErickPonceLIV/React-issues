## Ejercicio 1: React Issues

En el repositorio de GitHub de React, existe una sección donde se muestran los issues del proyecto: [https://github.com/facebook/react/issues](https://github.com/facebook/react/issues).

Desarrolla un programa en React con componentes que consulte la API de los issues del proyecto de React y muestre un listado de los issues en la pantalla, con las siguientes características:

- Al cargar la página, se mostrará el listado de issues, donde cada ítem del listado deberá:
  - Mostrar el id del issue.
  - Mostrar el título del issue.
  - Mostrar el nombre del usuario que abrió el issue.
  - Cuando se haga clic en un título, deberá redirigir al enlace que tiene el detalle del issue en GitHub (`html_url`).

**Plus:**
- Mostrar los labels a los que pertenece cada issue (ejemplo: Status: Unconfirmed, React 18, etc.).
- Elaborar una barra de búsqueda que permita filtrar los resultados traídos por la API.

**Consideraciones:**
- Las llamadas a la API deberán estar dentro del hook de React `useEffect()`.
- El endpoint a utilizar con la información de los issues es: `https://api.github.com/repos/facebook/react/issues`.
- Un ejemplo funcional podría ser similar a este: [https://josemiguelvazquez.github.io/react-issues-app/](https://josemiguelvazquez.github.io/react-issues-app/).
