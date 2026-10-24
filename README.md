# Draft Lab — Heroes of the Storm

Simulador local para practicar drafts de Ranked: mapa, bans, composiciones y un turno de pick aleatorio. No necesita servidor ni dependencias.

## Modos de turno

- **Aleatorio:** cualquier ronda de picks.
- **Último pick:** siempre el pick 10.
- **Última fase:** una ronda aleatoria entre los picks 7 y 10, después del segundo ban.

La opción elegida se conserva en este navegador.

Los picks simulados buscan armar composiciones razonables, pero no fuerzan que cada equipo cubra siempre los mismos roles; pueden quedar huecos para que el último pick también sea una decisión de tanque, sanador o bruiser.

## Probar localmente

Abre `index.html` en un navegador. Las imágenes de héroes y mapas requieren conexión a internet.

## Publicar con GitHub Pages

1. Sube este repositorio a GitHub.
2. En **Settings → Pages**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
4. Espera a que termine la publicación. El enlace del sitio aparecerá en esa misma sección.

El sitio publicado es accesible públicamente en internet.
