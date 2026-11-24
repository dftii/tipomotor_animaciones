# Tipomotor · animaciones de texto con GSAP

Colección de 97 animaciones de texto hechas con [GSAP](https://gsap.com/). Cada efecto tiene vista previa en directo, botón para repetirlo, código visible y botón para copiarlo.

**Funciones:**

- Escribe tu propio texto y míralo animado en todos los efectos compatibles.
- Cambia la velocidad (0,5× / 1× / 2×) y el tema (claro / oscuro).
- Los efectos se repiten al volver a verlos en pantalla y al pasar el ratón.
- Amplía cualquier efecto en grande.
- **Descarga un HTML que ya funciona** con el efecto, listo para abrir o modificar.
- Copia el enlace directo a un efecto (por ejemplo `#neon`) para compartirlo.
- Guarda favoritos (se recuerdan en tu navegador), filtra por categoría y busca por nombre.

**Web publicada:** https://dftii.github.io/tipomotor_animaciones/

## Categorías

| Categoría | Efectos |
|---|---|
| Entrada | 16 |
| Por letra | 19 |
| Cinética | 16 |
| Glitch y digital | 12 |
| Creativo | 12 |
| Párrafo | 11 |
| Scroll | 6 |
| Interactivo (reaccionan al ratón y a los clics) | 5 |

## Cómo usar un efecto en otro proyecto

1. Carga GSAP antes de cerrar `</body>`:

   ```html
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/gsap.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/SplitText.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/ScrollTrigger.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/TextPlugin.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/ScrambleTextPlugin.min.js"></script>
   ```

2. Pon la clase `titulo` al texto que quieras animar:

   ```html
   <h1 class="titulo">Hola, mundo</h1>
   ```

3. Registra los plugins y pega el código copiado desde la web:

   ```js
   gsap.registerPlugin(SplitText, ScrollTrigger, TextPlugin, ScrambleTextPlugin);
   // …código del efecto…
   ```

## Ver la web en local

Abre `index.html` en el navegador. No necesita instalación.
