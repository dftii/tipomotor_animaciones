# Tipomotor · animaciones de texto con GSAP

Colección de 57 animaciones de texto hechas con [GSAP](https://gsap.com/). Cada efecto tiene vista previa en directo, botón para repetirlo, código visible y botón para copiarlo.

**Funciones:** escribe tu propio texto y míralo animado, cambia la velocidad (0,5× / 1× / 2×), amplía cualquier efecto en grande, guarda favoritos (se recuerdan en tu navegador), filtra por categoría y busca por nombre.

**Web publicada:** https://dftii.github.io/tipomotor_animaciones/

## Categorías

| Categoría | Efectos |
|---|---|
| Entrada | 11 |
| Por letra | 11 |
| Cinética | 11 |
| Glitch y digital | 7 |
| Creativo | 7 |
| Párrafo | 7 |
| Scroll | 3 |

## Cómo usar un efecto en otro proyecto

1. Carga GSAP antes de cerrar `</body>`:

   ```html
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/gsap.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/SplitText.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/ScrollTrigger.min.js"></script>
   ```

2. Pon la clase `titulo` al texto que quieras animar:

   ```html
   <h1 class="titulo">Hola, mundo</h1>
   ```

3. Registra los plugins y pega el código copiado desde la web:

   ```js
   gsap.registerPlugin(SplitText, ScrollTrigger);
   // …código del efecto…
   ```

## Ver la web en local

Abre `index.html` en el navegador. No necesita instalación.

## Publicar con GitHub Pages

En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**. En uno o dos minutos la web aparece en la dirección de arriba.
