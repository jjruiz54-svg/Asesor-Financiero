# CLAUDE.md — Reglas del repositorio Asesor Financiero

Este archivo define las **reglas claras y obligatorias** para todo trabajo realizado en este repositorio, tanto por agentes de IA como por colaboradores humanos. Léelo antes de crear o modificar cualquier contenido.

## 1. Propósito del repositorio

Registrar y analizar las actividades financieras de 4 bolsas de valores (Colombia, Estados Unidos, Asia y Europa), incluyendo investigación de activos, oportunidades de inversión e historia de los instrumentos de los últimos 5 años, con atención especial al impacto de la geopolítica en la economía local y global.

Antes de cualquier análisis, lee [`PERFIL.md`](PERFIL.md) para entender el contexto y los intereses del analista.

## 2. Reglas de organización

1. **Cada bolsa tiene su carpeta** bajo `bolsas/` y NO se mezcla contenido entre bolsas. Un análisis comparativo entre mercados se guarda en la carpeta de la bolsa protagonista, con enlaces a las demás.
2. **Toda entrada va en la subcarpeta correcta**:
   - `investigacion-activos/` → fichas de análisis de un activo concreto.
   - `oportunidades-inversion/` → tesis de inversión con escenarios y riesgos.
   - `historia-instrumentos/` → comportamiento histórico (ventana mínima: 5 años).
   - `actividades/` → bitácora de eventos del mercado (resultados, decisiones de bancos centrales, noticias geopolíticas relevantes).
3. **Nomenclatura de archivos**: `AAAA-MM-DD-ticker-o-tema.md` en minúsculas y sin espacios. Ejemplo: `2026-07-15-ecopetrol-analisis.md`.
4. **Formato**: todo documento se escribe en **Markdown** y en **español**. Los términos técnicos en inglés se mantienen cuando son estándar del mercado (spread, yield, ETF, etc.).

## 3. Reglas para los sub-agentes

1. Cada bolsa es manejada **exclusivamente** por su sub-agente especializado, definido en `.claude/agents/`:
   - `bolsa-colombia` → Bolsa de Valores de Colombia (bvc).
   - `bolsa-eeuu` → NYSE y Nasdaq.
   - `bolsa-asia` → Tokio, Hong Kong, Shanghái, Shenzhen, Seúl, Singapur.
   - `bolsa-europa` → Euronext, LSE, Deutsche Börse, BME, SIX.
2. Los sub-agentes buscan información **únicamente en las fuentes de confianza** listadas en su propia ficha. Si una fuente no está en la lista, no se usa sin aprobación explícita del dueño del repositorio.
3. Un sub-agente **no escribe** en la carpeta de otra bolsa.
4. Si una tarea abarca varias bolsas, se invoca a cada sub-agente por separado y se consolida el resultado indicando qué agente aportó cada sección.

## 4. Reglas de calidad de la información

1. **Toda cifra lleva fuente y fecha.** Formato: `(Fuente: nombre, AAAA-MM-DD)`. Sin fuente, el dato no entra al repositorio.
2. **Prohibido inventar datos.** Si un dato no se pudo verificar, se escribe explícitamente "dato no verificado" o se omite.
3. **Distinguir hecho de opinión.** Los hechos se redactan en indicativo con su fuente; las opiniones y proyecciones se marcan claramente como tales (sección "Opinión del analista" o "Escenarios").
4. **Ventana histórica mínima de 5 años** para todo análisis de instrumentos en `historia-instrumentos/`.
5. **Contexto geopolítico obligatorio**: toda tesis de inversión debe incluir una sección sobre riesgos y catalizadores geopolíticos.
6. **Actualidad**: indicar siempre la fecha de corte de los datos. Un análisis sin fecha de corte se considera incompleto.

## 5. Plantilla mínima de una ficha de análisis

```markdown
# [Ticker] — [Nombre del activo]

- **Bolsa / mercado:**
- **Fecha de análisis:**
- **Fecha de corte de datos:**
- **Analista / agente:**

## Resumen ejecutivo
(3–5 líneas)

## Datos clave
(precio, capitalización, múltiplos, dividendos — cada uno con fuente y fecha)

## Comportamiento últimos 5 años
(rendimiento anual, máximos/mínimos, eventos relevantes)

## Contexto geopolítico y macroeconómico
(cómo afecta la coyuntura local y global a este activo)

## Escenarios
- Alcista:
- Base:
- Bajista:

## Riesgos

## Fuentes consultadas
```

## 6. Reglas de conducta y alcance

1. **Nada de lo escrito aquí es asesoría financiera profesional.** Todo documento debe poder leerse como análisis educativo.
2. **No se registran datos personales sensibles** (números de cuenta, montos reales de portafolio, credenciales). El perfil del analista en `PERFIL.md` es el único contexto personal permitido.
3. **No se suben archivos binarios pesados** (>5 MB). Los gráficos se prefieren como imágenes ligeras o descripciones con datos tabulados.
4. **Commits descriptivos y en español**: `Agregar análisis de Ecopetrol Q2 2026`, `Actualizar histórico del Nikkei 225`.
5. **Idioma de trabajo:** español. Resúmenes de fuentes en inglés u otros idiomas se traducen al documentar.
