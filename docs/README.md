# GitHub Pages

Esta carpeta existe únicamente para publicar un **índice del repositorio** como página web mediante **GitHub Pages**.

- `index.html` es la página de inicio: enlaza, agrupadas por las 5 categorías del repositorio (Colombia, Estados Unidos, Asia, Europa, Criptomonedas) más los informes generales de `informes-mercados/`, a cada ficha `.md` (vía GitHub) y a su gráfico interactivo. Se actualiza a mano cada vez que se publica un nuevo análisis en `bolsas/` o `informes-mercados/`.
- `graficos/` contiene **copias** de los gráficos `.html` interactivos citados desde `index.html`, para que GitHub Pages pueda servirlos (Pages solo sirve archivos dentro de esta carpeta). El original de cada gráfico sigue siendo la fuente de verdad en la carpeta de la ficha correspondiente (`bolsas/.../*-grafico.html`); si un gráfico se actualiza allí, hay que volver a copiarlo aquí.

## Activación (paso manual, una sola vez)

GitHub Pages requiere habilitarse desde la configuración del repositorio — esto no se puede hacer vía API/commits, solo desde la interfaz de GitHub:

1. Ir a **Settings → Pages** en el repositorio.
2. En "Build and deployment" → **Source**: `Deploy from a branch`.
3. **Branch**: `main` — **Folder**: `/docs`.
4. Guardar.

La página quedará disponible en: `https://jjruiz54-svg.github.io/Asesor-Financiero/`

**Nota:** la fuente de Pages está configurada sobre la rama `main`. Los cambios hechos en una rama de trabajo (p. ej. `claude/...`) solo se reflejan en la página publicada después de fusionarse a `main`.
