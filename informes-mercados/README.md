# 📰 Informes de Mercados Consolidados

Carpeta para informes de seguimiento **ad hoc** que cubren simultáneamente las 5 categorías del repositorio (Colombia, Estados Unidos, Europa, Asia y criptomonedas), consolidados por el orquestador a partir de los sub-agentes de cada bolsa.

A diferencia de las fichas estándar de `bolsas/*/`, estos informes no pertenecen a una sola bolsa "protagonista": son un corte transversal de todos los mercados en una fecha dada, junto con una sección de oportunidades de inversión.

## Nomenclatura

`AAAA-MM-DD-informe-mercados.md` — informe general (resumen ejecutivo + datos clave + informe cualitativo + fuentes, por mercado).
`AAAA-MM-DD-oportunidades-inversion.md` — oportunidades de inversión identificadas ese corte, con tesis y nivel de riesgo.
`AAAA-MM-DD-informe-mercados-grafico.html` — artefacto HTML autocontenido (modo claro/oscuro, gráficas y tabla de datos) con el mismo contenido, siguiendo la skill **dataviz** del repositorio.

## Reglas

Aplican las mismas reglas de calidad de `CLAUDE.md`: toda cifra con fuente y fecha, distinción hecho/opinión, contexto geopolítico, y el disclaimer de que el contenido es informativo y no constituye asesoría financiera personalizada.
