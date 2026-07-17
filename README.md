# 📊 Asesor Financiero

Repositorio de análisis y seguimiento de los mercados financieros globales, organizado en **5 categorías**: las 4 principales bolsas de valores del mundo, más el mercado de criptomonedas. Cada categoría es gestionada por un **sub-agente especializado** que realiza búsquedas exclusivamente en fuentes de confianza.

## 🎯 Objetivo

Llevar un registro estructurado de las actividades financieras de las diferentes bolsas:

- **Investigación de activos** — análisis fundamental y técnico de acciones, ETFs, bonos e índices.
- **Oportunidades de inversión** — identificación y documentación de oportunidades con su tesis de inversión.
- **Historia de los instrumentos** — comportamiento de los instrumentos en los **últimos 5 años** (2021–2026).
- **Impacto geopolítico** — cómo la geopolítica afecta la economía local y global.

## 🌎 Las 5 categorías

| # | Categoría | Carpeta | Sub-agente | Índices / cobertura de referencia |
|---|-----------|---------|------------|----------------------|
| 1 | Bolsa de Valores de Colombia (bvc) | [`bolsas/colombia/`](bolsas/colombia/) | `bolsa-colombia` | MSCI COLCAP |
| 2 | Bolsa de Valores Estadounidense | [`bolsas/estados-unidos/`](bolsas/estados-unidos/) | `bolsa-eeuu` | S&P 500, Nasdaq, Dow Jones |
| 3 | Bolsas de Valores de Asia | [`bolsas/asia/`](bolsas/asia/) | `bolsa-asia` | Nikkei 225, Hang Seng, SSE, KOSPI |
| 4 | Bolsas de Valores de Europa | [`bolsas/europa/`](bolsas/europa/) | `bolsa-europa` | STOXX 600, DAX, FTSE 100, IBEX 35 |
| 5 | Criptomonedas | [`bolsas/criptomonedas/`](bolsas/criptomonedas/) | `criptomonedas` | Top 10 por capitalización de mercado + WLD (obligatoria si no está en el top 10) |

## 📁 Estructura del repositorio

```
Asesor-Financiero/
├── README.md                  ← este archivo
├── CLAUDE.md                  ← reglas claras del repositorio (lectura obligatoria)
├── PERFIL.md                  ← perfil y contexto del analista
├── .claude/agents/            ← definición de los 5 sub-agentes especializados
│   ├── bolsa-colombia.md
│   ├── bolsa-eeuu.md
│   ├── bolsa-asia.md
│   ├── bolsa-europa.md
│   └── criptomonedas.md
├── bolsas/
│   ├── colombia/
│   ├── estados-unidos/
│   ├── asia/
│   ├── europa/
│   └── criptomonedas/
│       ├── investigacion-activos/      ← fichas de análisis por activo
│       ├── oportunidades-inversion/    ← tesis de inversión documentadas
│       ├── historia-instrumentos/      ← histórico de 5 años por instrumento (o desde su lanzamiento)
│       └── actividades/                ← bitácora de actividades del mercado
└── informes-mercados/          ← informes ad hoc que cruzan las 5 categorías (ver README propio)
```

## 🤖 Sub-agentes especializados

Cada bolsa es manejada por un sub-agente que:

1. Busca información **únicamente en las fuentes de confianza** definidas en su ficha (`.claude/agents/`).
2. Documenta sus hallazgos siguiendo las plantillas y reglas de [`CLAUDE.md`](CLAUDE.md).
3. Cita siempre la fuente y la fecha de cada dato.
4. Considera el contexto geopolítico en cada análisis.

## ⚠️ Aviso legal

Este repositorio tiene fines **educativos y de análisis personal**. Nada de lo aquí contenido constituye asesoría financiera profesional ni recomendación de compra o venta de valores. Toda decisión de inversión es responsabilidad exclusiva de quien la toma.
