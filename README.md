# Taller de Arcilla

App para el trabajo de artes visuales: arrancás con un bloque de arcilla digital, lo modelás como si fuera de verdad y después la app saca fotos de la escultura desde todos los ángulos, para usarlas como boceto.

## Cómo abrirla

Abrí `index.html` en el navegador (Chrome, Edge, Firefox o Safari). Necesita internet para cargar Three.js.

### Publicarla como página web (GitHub Pages)

1. En GitHub: **Settings → General → Danger Zone → Change visibility → Public** (Pages gratis sólo funciona con repos públicos).
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, elegí la rama `ccr-2fe21f6d-bobdog` y la carpeta `/ (root)`, y tocá **Save**.
3. En un par de minutos la página queda en `https://jesusteama-w.github.io/Trabajo-de-artes-visuales-/`.

## Reiniciar

El botón **Reiniciar** (arriba) vuelve al bloque del principio. Si lo tocaste sin querer, **Deshacer** recupera la escultura.

## Herramientas

| Tecla | Herramienta | Qué hace |
|---|---|---|
| 0 | Mano | Gira la vista sin tocar la arcilla |
| 1 | Añadir | Suma capas de arcilla |
| 2 | Quitar | Saca arcilla, como con una estica de lazo |
| 3 | Inflar | Hincha la zona hacia afuera |
| 4 | Alisar | Empareja la superficie (también con Shift) |
| 5 | Aplanar | Hace caras planas |
| 6 | Pellizcar | Junta la arcilla y afila bordes |
| 7 | Surco | Marca líneas y pliegues |
| 8 | Mover | Agarra un pedazo y lo estira o lo empuja |

- **Ctrl** mientras modelás: hace el efecto contrario.
- **[ y ]**: cambian el tamaño del pincel. **X**: simetría izquierda/derecha.
- Arrastrar fuera de la pieza gira la vista, la rueda hace zoom y el clic derecho desplaza.
- En el celular: un dedo sobre la pieza modela, un dedo afuera gira y dos dedos hacen zoom.
- **Ctrl+Z / Ctrl+Shift+Z**: deshacer y rehacer.

## Fotos para el boceto

En el panel **Fotos del boceto** elegís:

- **Ángulos:** 6 vistas (frente, derecha, atrás, izquierda, arriba, abajo), 14 vistas (esas 6 más cuatro ¾ y cuatro en picado) o una vuelta completa de 24 fotos, una cada 15°.
- **Estilo:** *Boceto* (gris con contorno negro, fácil de copiar), *Arcilla* (con color y sombra) o *Silueta* (sólo la forma en negro).
- **Cámara:** *Plana* (sin perspectiva, con una regla en cm) o *Perspectiva*.

Después de sacar las fotos podés descargarlas todas en un `.zip` o bajar la **hoja de vistas**, una sola imagen con todos los ángulos juntos.

## Medidas reales

Con **Empezar con un bloque nuevo…** ponés el ancho, alto y fondo de tu bloque de arcilla real en centímetros. Abajo a la derecha siempre ves cuánto mide la escultura, y la regla de las fotos usa esas medidas.

## Guardar

La app guarda sola en el navegador. Con **Guardar** te bajás un archivo `.json` que después abrís con **Abrir**.
