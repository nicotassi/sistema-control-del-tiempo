# Sistema de Control de Tiempo

App web instalable (PWA) basada en *Master Your Time, Master Your Life* de Brian Tracy.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app (contenido, estilos y lógica) |
| `manifest.webmanifest` | Nombre, colores e íconos para instalarla como app |
| `sw.js` | Service worker: hace la app instalable y la deja funcionar sin internet |
| `icons/` | Íconos de la app |

## Publicarla con GitHub Pages (una sola vez)

1. En GitHub, abrí el repo → **Settings** → **Pages**.
2. En *Build and deployment* → *Source*, elegí **Deploy from a branch**.
3. Branch: **main**, carpeta **/ (root)** → **Save**.
4. En 1–2 minutos queda online en:
   `https://nicotassi.github.io/sistema-control-del-tiempo/`

## Instalarla

- **Android (Chrome):** abrir el link → menú ⋮ → **Instalar app** / *Agregar a pantalla principal*.
- **iPhone (Safari):** abrir el link → botón Compartir → **Agregar a inicio**.
- **Computadora (Chrome/Edge):** ícono de instalar en la barra de direcciones.

## Cómo hacer cambios

Cada cambio se guarda como un commit en este repo, así que queda persistente y con historial.
Al subir un cambio a `main`, GitHub Pages lo republica solo y la app instalada toma la versión
nueva la próxima vez que se abre con conexión.
