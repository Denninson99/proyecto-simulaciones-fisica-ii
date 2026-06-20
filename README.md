# Simulaciones de Física II

Proyecto web listo para subir a GitHub Pages.

## Estructura

```text
index.html
assets/
  css/
    styles.css
simulaciones/
  gauss/
    index.html
    sketch.js
```

## Cómo abrir localmente

Abre `index.html` en el navegador. Desde ahí se entra a la simulación de Gauss.

## Cómo subir a GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todo el contenido de esta carpeta, no solo el archivo index.html.
3. En el repositorio entra a Settings > Pages.
4. En Source selecciona Deploy from a branch.
5. Selecciona branch `main` y carpeta `/root`.
6. Guarda y espera a que GitHub genere el link.

## Cómo agregar las otras simulaciones

Crea una carpeta nueva dentro de `simulaciones/`, por ejemplo:

```text
simulaciones/potencial/
  index.html
  sketch.js
```

Después edita el `index.html` principal y cambia una tarjeta pendiente para que apunte a esa ruta:

```html
<a class="sim-card activa" href="simulaciones/potencial/index.html">
```
