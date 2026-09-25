# WLD — Worldcoin (Actualización)

- **Bolsa / mercado:** Mercado global de criptomonedas (activo digital, red propia World Chain / Ethereum L2). No cotiza en ninguna bolsa tradicional de las cubiertas por este repositorio.
- **Fecha de análisis:** 2026-09-25
- **Fecha de corte de datos:** 2026-09-25. Las cifras de precio, capitalización y ranking provienen de fichas de CoinMarketCap y CoinGecko **recuperadas por búsqueda web el 2026-09-25**. No fue posible el acceso directo en vivo a CoinMarketCap.com, CoinGecko.com, la API de CoinGecko, CoinDesk.com ni TheBlock.co (error `EGRESS_BLOCKED` del proxy de salida del entorno), por lo que la hora exacta de cada cifra "en vivo" no se pudo verificar. Las cifras recuperadas son coherentes con los precios de Bitcoin publicados para el 24 y 25 de septiembre de 2026 (~US$83.400–85.200), lo que indica que corresponden a esa ventana.
- **Analista / agente:** Sub-agente `criptomonedas` (Claude Code)
- **Documentos relacionados:** `2026-07-17-wld-analisis.md` (ficha base completa) y `2026-08-30-wld-actualizacion.md` (actualización anterior). Este documento es una actualización puntual y no reemplaza la ficha base.

## Nota de cobertura obligatoria (regla del repositorio)

Se volvió a verificar el top 10 de criptomonedas por capitalización de mercado a la fecha de corte. **WLD no forma parte del top 10 por capitalización de mercado a la fecha de corte; se incluye de forma obligatoria por directriz del repositorio**, como posición 11.

*Glosario rápido:* la **capitalización de mercado** es el precio multiplicado por las unidades en circulación. La **dominancia de Bitcoin** es la parte del valor total del mercado cripto que corresponde a BTC. Una **stablecoin** es un token diseñado para mantener un valor fijo, normalmente US$1.

### Ranking top 10 vigente (CoinMarketCap, consulta por búsqueda web del 2026-09-25)

| Puesto (CMC) | Activo | Precio (USD) | Cap. de mercado (USD) | Var. 24h | Var. aprox. desde la ficha del 30-ago | Fuente / fecha |
|---|---|---|---|---|---|---|
| 1 | Bitcoin (BTC) | 84.184,47 | 1,691 billones | +0,34% | +8,4% (desde ~77.678 el 29-ago) | CoinMarketCap, 2026-09-25 |
| 2 | Ethereum (ETH) | 2.676,17 | 326.703 millones | -0,52% | +7,3% a +9,2% (desde ~2.450–2.494) | CoinMarketCap, 2026-09-25 |
| 3 | Tether (USDT) | 0,9997 | 183.723 millones | -0,01% | Stablecoin; sin variación relevante | CoinMarketCap, 2026-09-25 |
| 4 | BNB | 778,62 | 103.681 millones | +1,09% | +12,4% (desde ~692,5 el 25-ago) | CoinMarketCap, 2026-09-25 |
| 5 | XRP | 1,58 (CoinGecko: 1,53) | 99.197 millones | +4,65% (CoinGecko: +1,70%) | +12,9% (desde ~1,40 el 25-ago) | CoinMarketCap / CoinGecko, 2026-09-25 |
| 6 | USD Coin (USDC) | Referenciada a US$1; precio exacto: dato no verificado | 75.440 millones (CoinGecko) | dato no verificado | Stablecoin | CoinMarketCap (puesto) / CoinGecko (cap.), 2026-09-25 |
| 7 | Solana (SOL) | 114,86 | 67.491 millones | -3,87% | No comparable (en agosto se citó un rango de ~71–105, demasiado amplio) | CoinMarketCap, 2026-09-25 |
| 8 | TRON (TRX) | 0,3368 | 31.987 millones | -1,02% | dato no verificado (sin precio de referencia en agosto) | CoinMarketCap, 2026-09-25 |
| 9 | **Zcash (ZEC)** — nuevo en el top 10 | 1.549,71 | 26.169 millones | dato no verificado | dato no verificado (ver eventos) | CoinMarketCap, 2026-09-25 |
| 10 | Hyperliquid (HYPE) | 93,67 | 20.794 millones (cifra de CoinGecko, donde ocupa el puesto #11) | +3,03% | dato no verificado | CoinMarketCap / CoinGecko, 2026-09-25 |
| *(fuera: 11 en CMC)* | *Dogecoin (DOGE)* | *0,098487* | *16.918 millones (CoinGecko: 15.155 millones, puesto #12)* | *+6,42%* | *Salió del top 10 de CoinMarketCap* | *CoinMarketCap / CoinGecko, 2026-09-25* |
| **11 (obligatorio)** | **Worldcoin (WLD)** | **0,431836 (CMC) / 0,4569 (CoinGecko)** | **1.577 millones (CMC) / 1.668 millones (CoinGecko)** | **+5,99% (CMC) / +12,50% (CoinGecko)** | **+14,3% (CMC vs. CMC)** | **CoinMarketCap / CoinGecko, 2026-09-25** |

- **Cap. total del mercado cripto:** ~US$2,87 billones, -0,26% en 24h; volumen 24h ~US$102.300 millones (Fuente: CoinMarketCap, 2026-09-25).
- **Dominancia de Bitcoin:** 58,58% (Fuente: CoinMarketCap, 2026-09-25), frente a ~57,4% en la ficha del 30-ago.
- Las variaciones desde el 30-ago de BTC, ETH, BNB y XRP las calculó el analista con los precios de referencia de la ficha `2026-08-30-wld-actualizacion.md`. Esos precios provienen de fuentes secundarias de los días 25 a 29 de agosto, así que las variaciones son aproximadas.

**Cambio de composición respecto de agosto (hecho relevante):** en CoinMarketCap, Zcash (ZEC) entró al top 10 en el puesto #9 y Dogecoin (DOGE) bajó al #11 (Fuente: CoinMarketCap, 2026-09-25). **Nota metodológica:** CoinMarketCap y CoinGecko no coinciden en las posiciones 10 a 12. En CoinGecko, HYPE está en el #11 y DOGE en el #12. El activo que ocupa el #10 en CoinGecko es un **dato no verificado**, porque no se pudo acceder a la lista completa. Por consistencia, este documento usa el ranking de CoinMarketCap. Los puestos #1 a #8 coinciden en ambas plataformas en todos los casos que se pudieron cruzar (USDT #3, XRP #5 y USDC #6 aparecen confirmados en las dos).

## Resumen ejecutivo

Al 25 de septiembre de 2026, WLD cotiza en ~US$0,43–0,46 con una capitalización de ~US$1.577–1.668 millones, según la plataforma. Eso supone una subida de ~14% frente al 30 de agosto (comparando CoinMarketCap con CoinMarketCap). WLD sigue fuera del top 10: está en el #50 de CoinMarketCap y el #59 de CoinGecko. El catalizador propio del mes fue el lanzamiento de **World Money** (17-sep), una super app financiera de autocustodia disponible en más de 150 países. En el contexto macro hubo tres hechos clave: la Fed subió tasas por primera vez en más de tres años (16-sep), la Ley CLARITY fracasó en el Senado de EE. UU. (15-sep) y después llegó un fuerte rebote del mercado, con Bitcoin por encima de US$85.000 el 21-sep. Aun así, WLD subió menos que el mercado en la última semana: +5,3% frente a +9,4% del mercado global, según CoinGecko.

## Datos clave

- **Puesto en el ranking:** #50 en CoinMarketCap y #59 en CoinGecko (Fuente: CoinMarketCap / CoinGecko, 2026-09-25). Está fuera del top 10 y se incluye como **posición 11 obligatoria**. Fecha de corte del ranking: 2026-09-25.
- **Precio (spot):** US$0,431836 (Fuente: CoinMarketCap, 2026-09-25); US$0,4569 (Fuente: CoinGecko, 2026-09-25); US$0,41 "al 24 de septiembre de 2026" (Fuente: CoinDesk, página de precio de WLD, 2026-09-24). La diferencia entre plataformas se explica por la hora de consulta, que no se pudo verificar, y por la metodología de agregación de cada una.
- **Capitalización de mercado:** US$1.576.959.167 (Fuente: CoinMarketCap, 2026-09-25); US$1.668.447.217 (Fuente: CoinGecko, 2026-09-25).
- **Volumen 24h:** US$342.701.668 (Fuente: CoinMarketCap, 2026-09-25); US$389.715.230 (Fuente: CoinGecko, 2026-09-25); US$272,65 millones (Fuente: CoinDesk, 2026-09-24).
- **Variación 24h:** +5,99% (Fuente: CoinMarketCap, 2026-09-25); +12,50% (Fuente: CoinGecko, 2026-09-25). Son cifras intradía que dependen de la hora de consulta.
- **Variación 7 días:** +5,3%, frente a +9,4% del mercado cripto global en el mismo periodo (Fuente: CoinGecko, 2026-09-25).
- **Suministro circulante (implícito):** ~3.652 millones de WLD. El analista lo calculó dividiendo la capitalización entre el precio, y ambas plataformas dan el mismo resultado. Es ~0,9% más que los ~3.617,5 millones del 30-ago (Fuente: CoinMarketCap, 2026-08-30). CoinGecko indica "3,7 mil millones de tokens negociables" (Fuente: CoinGecko, 2026-09-25).
- **Máximo y mínimo históricos:** máximo (ATH) de US$11,74 y mínimo (ATL) de US$0,2300. El precio actual está un 96,10% por debajo del máximo y un 98,70% por encima del mínimo (Fuente: CoinGecko, 2026-09-25).
- **Dividendos / múltiplos:** no aplican. WLD es un token y no reparte dividendos ni tiene utilidades por acción.

## Variación desde el 30 de agosto de 2026 (fecha de corte de la actualización anterior)

| Métrica | 30-ago-2026 | 25-sep-2026 | Variación |
|---|---|---|---|
| Precio CoinMarketCap | US$0,377844 (CMC, 2026-08-30) | US$0,431836 (CMC, 2026-09-25) | **+14,3%** |
| Precio CoinGecko | US$0,41158 (CoinGecko, 2026-08-27) | US$0,4569 (CoinGecko, 2026-09-25) | +11,0% (la base es del 27-ago) |
| Cap. CoinMarketCap | US$1.366,9 millones (CMC, 2026-08-30) | US$1.577,0 millones (CMC, 2026-09-25) | +15,4% |
| Cap. CoinGecko | US$1.488,2 millones (CoinGecko, 2026-08-27) | US$1.668,4 millones (CoinGecko, 2026-09-25) | +12,1% |
| Puesto CMC / CoinGecko | #50 / #59 | #50 / #59 | Sin cambio |
| Suministro circulante | ~3.617,5 millones (CMC, 2026-08-30) | ~3.652 millones (implícito, CMC, 2026-09-25) | ~+0,9% (dilución) |

Las variaciones las calculó el analista con las cifras citadas. La capitalización creció algo más que el precio (+15,4% frente a +14,3% en CMC) porque aumentó el suministro circulante: es el efecto de la **dilución** (más tokens en circulación por la emisión programada).

**Comparación con el mercado:** en el mismo periodo, BTC subió ~+8,4% y ETH ~+7–9% (ver tabla del ranking). WLD superó a los grandes en el mes, pero en la última semana subió menos que el mercado (+5,3% frente a +9,4%, según CoinGecko, 2026-09-25).

## Comportamiento histórico (resumen)

WLD se lanzó el 24 de julio de 2023, así que su **historial disponible empieza en esa fecha y es inferior a la ventana mínima de 5 años**. El detalle histórico está en la ficha base `2026-07-17-wld-analisis.md`. En resumen, pasó de un ATH de US$11,74 a un ATL de US$0,2300 (Fuente: CoinGecko, 2026-09-25). El mínimo se alcanzó en mayo de 2026 (ver ficha base y ficha del 30-ago). Desde el mínimo, el precio casi se ha duplicado (+98,70%).

## Eventos relevantes desde el 30 de agosto de 2026

### Hechos específicos de WLD / World

1. **Lanzamiento de World Money (17-sep-2026).** World, el proyecto antes llamado Worldcoin, lanzó una super app financiera de **autocustodia** (el usuario controla sus propias llaves) en más de 150 países. Reúne pagos con stablecoins, trading, rendimientos y cuentas virtuales, y admite saldos en ocho monedas. Stripe permite en EE. UU. convertir fondos de Apple Pay en stablecoins, y la app se integra con Kalshi y Morpho. La verificación con World ID da acceso a recompensas mayores (Fuente: The Block, 2026-09-17; World, blog oficial "Introducing World Money", 2026-09). La función "Vault" pasó a llamarse "Earn", con un esquema de rendimiento sobre varios activos (Fuente: CoinMarketCap, sección "Latest updates" de WLD, 2026-09).
2. **Reacción del precio.** CoinMarketCap atribuyó una subida del 3,68% al lanzamiento y otra posterior del 11% a la suma de tres factores: el lanzamiento, que la empresa Eightco reveló tener **302 millones de WLD** en tesorería, y el rebote general del mercado tras la subida de tasas de la Fed (Fuente: CoinMarketCap Top Stories, 2026-09). La fecha exacta de cada nota es un dato no verificado.
3. **ETF de Grayscale sobre WLD (contexto, sigue pendiente).** Grayscale presentó en julio de 2026 un formulario S-1 (registro de valores ante la SEC) para un "Grayscale Worldcoin ETF", con ticker GWLD en Nasdaq, BitGo como custodio y BNY Mellon como agente de transferencia (Fuente: SEC EDGAR, S-1 del 2026-07-20; Decrypt, 2026-07). **No se encontró evidencia de aprobación ni de lanzamiento** a la fecha de corte, así que su estado actual es un dato no verificado.
4. **Frente regulatorio biométrico.** En las fuentes de confianza consultadas (CoinDesk, The Block, Decrypt) **no apareció ninguna nueva prohibición ni sanción** contra World entre el 30-ago y el 25-sep-2026. Siguen vigentes las restricciones ya documentadas en fichas anteriores, entre ellas Hong Kong, España, Brasil, Kenia y Corea del Sur. La resolución final del caso español (AEPD) sigue siendo un **dato no verificado**.

### Hechos de mercado y regulación que afectaron a todo el sector

5. **Fracaso de la Ley CLARITY en el Senado de EE. UU. (15-sep-2026).** La moción de *cloture* (el trámite que corta el debate y exige 60 votos) perdió 49 a 50. La ley buscaba repartir la supervisión cripto entre la SEC y la CFTC y dar a la CFTC autoridad sobre los mercados spot. Según CoinDesk, el resultado pone fin en la práctica al trabajo legislativo sobre estructura de mercado en el Senado para 2026. Ese día BTC cayó de ~US$77.200 a ~US$75.600 y cerró cerca de US$75.800, con una baja de ~3,2% (Fuente: CoinDesk, 2026-09-15; The Block, 2026-09-15; Decrypt, 2026-09-15). The Block mencionó como punto de bloqueo una cláusula ética relacionada con los ingresos cripto de Trump (Fuente: The Block, 2026-09-15).
6. **Primera subida de tasas de la Fed en más de tres años (16-sep-2026).** La Fed subió 25 puntos básicos por unanimidad, según el titular de The Block. El rango de fondos federales pasó de 3,50–3,75% a 3,75–4,00%. El presidente de la Fed, Kevin Warsh, dijo que le costaría "describir las condiciones financieras como restrictivas", y 16 de los 18 miembros proyectan al menos una subida más este año (Fuente: The Block, 2026-09-16; CoinDesk, 2026-09-16). *Corrección respecto de la ficha del 30-ago:* allí se llamó a Warsh "gobernador". Según las fuentes consultadas, es **presidente (Chair)** de la Fed desde mayo de 2026.
7. **Rebote pese a la subida de tasas.** Tras la decisión, BTC recuperó los US$80.000 el 18-sep, con subidas de ~10% en SOL y HYPE (Fuente: The Block, 2026-09-18). El 21-sep superó los US$85.000 por primera vez desde enero, impulsado por un **short squeeze**: el cierre forzado de apuestas bajistas, con ~US$648 millones en posiciones cortas liquidadas (Fuente: CoinDesk, 2026-09-21; The Block, 2026-09-21). Ese mismo día Strategy retomó sus compras de BTC (Fuente: CoinDesk, 2026-09-21).
8. **Proyecto de ley de reserva estratégica de Bitcoin (adopción estatal).** El Comité de Servicios Financieros de la Cámara de Representantes aprobó el "American Reserve Modernization Act", que codificaría la reserva de bitcoin del gobierno con un bloqueo mínimo de 20 años. La votación siguió líneas de partido. Aún debe pasar por el pleno de la Cámara y no tiene contraparte aprobada en el Senado (Fuente: The Block, 2026-09-16; Decrypt, 2026-09; CoinDesk, 2026-09-23).
9. **Zcash entra al top 10.** ZEC superó los US$1.000 el 4-sep y los US$1.616 el 23-sep (Fuente: CoinDesk, 2026-09-04 y 2026-09-23). El ETF spot de Grayscale sobre Zcash (ZCSH, NYSE Arca) recibió entradas de ~US$233 millones y planea un split de 3 por 1 (Fuente: The Block, 2026-09-18).
10. **CFTC y Hyperliquid.** La CFTC envió a la Oficina de Gestión y Presupuesto (OMB) de la Casa Blanca una propuesta de regulación de mercados de criptoactivos. Hyperliquid marcó un máximo histórico por encima de US$90 tras lanzar préstamos con HYPE y BTC como colateral (Fuente: The Block, 2026-09-08 y 2026-09-18).

## Contexto geopolítico y macroeconómico

**Hechos:**

- **Política monetaria de EE. UU.:** la Fed pasó a una fase de endurecimiento (rango de 3,75–4,00% tras el 16-sep) y la mayoría del comité anticipa otra subida en 2026 (Fuente: The Block, 2026-09-16). En teoría, tasas más altas encarecen el dinero y reducen el apetito por activos de riesgo como las criptomonedas. Sin embargo, la subida ya estaba descontada en un 92% según CME FedWatch (Fuente: The Block / CoinDesk, 2026-09-16), y el mercado cripto subió después de la decisión.
- **Petróleo y Oriente Medio:** CoinDesk vinculó el rebote cripto del 21 y 22 de septiembre a la caída del petróleo, que favoreció a los activos de riesgo, y el 25-sep reportó un nuevo descenso del crudo "por avances en Oriente Medio" (Fuente: CoinDesk, 2026-09-21, 2026-09-22 y 2026-09-25). El 1-sep, The Block había reportado un repunte del petróleo junto con más apuestas a una subida de tasas (Fuente: The Block, 2026-09-01).
- **Regulación en EE. UU. (SEC / CFTC):** sin la Ley CLARITY, el reparto de competencias entre la SEC y la CFTC sigue sin base legal. La vía administrativa continúa con la propuesta de la CFTC en revisión en la OMB y con los ETF cripto aprobados bajo estándares genéricos de listado, como el de Zcash (Fuente: CoinDesk, 2026-09-15; The Block, 2026-09-18).
- **Unión Europea (MiCA):** el periodo transitorio de MiCA terminó el 1 de julio de 2026. Desde esa fecha, todo proveedor de servicios cripto sin licencia MiCA que atienda a clientes de la UE incumple el derecho europeo, y ESMA pidió un cierre ordenado de sus operaciones (Fuente: ESMA, declaración pública de junio de 2026). Además, está en curso una revisión del marco, a veces llamada "MiCA 2.0" (Fuente: CoinDesk, 2026-07-02). Para World, la supervisión de datos biométricos en la UE depende del RGPD, más que de MiCA.
- **Asia:** el regulador financiero de Corea del Sur publicó un plan para tokenizar "todo tipo" de valores en tres etapas a partir de 2027, con liquidación prevista en stablecoins (Fuente: The Block, 2026-09-04). Hong Kong mantiene su régimen de licencias de stablecoins para grupos bancarios (Fuente: CoinDesk, 2026-05-27). En septiembre de 2026 no se encontraron cambios nuevos en China, Japón o Singapur que afecten directamente a WLD: dato no verificado.
- **Adopción estatal:** el proyecto de reserva estratégica de bitcoin avanzó en comité (ver evento 8).

**Opinión del analista (no es un dato verificado):** septiembre muestra que el mercado cripto puede subir aunque la Fed endurezca su política, si la subida ya estaba descontada y otros factores empujan en sentido contrario, como la caída del petróleo o el cierre forzado de posiciones cortas. Para WLD, el factor propio (World Money) parece haber pesado más en la primera mitad del mes. En la última semana, el capital especulativo se fue más hacia BTC, ZEC y HYPE. Para el lector colombiano, un entorno de tasas altas en EE. UU. tiende a fortalecer el dólar, lo que también afecta a quien compra cripto con pesos.

## Escenarios

*Estas proyecciones son opinión del analista y un ejercicio de escenarios, no datos verificados ni asesoría financiera. Actualizan los escenarios de la ficha del 30-ago.*

- **Alcista:** World Money logra tracción medible (usuarios activos, volumen en stablecoins) y el ETF de Grayscale sobre WLD recibe luz verde. En ese caso, WLD podría consolidarse por encima de US$0,50 y buscar la zona de US$0,60–1,00, siempre que la Fed no acelere las subidas.
- **Base:** WLD sigue en un rango de ~US$0,35–0,55, sube y baja con el mercado general y reacciona a noticias puntuales, mientras la dilución por emisión (~+0,9% de suministro al mes en este periodo) frena las subidas.
- **Bajista:** la Fed aplica la subida adicional proyectada, el apetito por riesgo se enfría y aparece una nueva sanción biométrica en un mercado grande (UE o Asia). WLD podría volver a la zona de US$0,25–0,30, cerca de su ATL de US$0,2300.

## Riesgos

*Riesgos identificados para fines educativos; no constituyen recomendación. Siguen vigentes los riesgos de la ficha base: datos biométricos, dilución, concentración de la gobernanza, baja liquidez relativa, correlación macro y riesgo narrativo.*

1. **Política monetaria:** 16 de 18 miembros de la Fed proyectan otra subida en 2026 (Fuente: The Block, 2026-09-16). Un activo pequeño como WLD suele caer más que BTC cuando el mercado busca refugio.
2. **Vacío legislativo en EE. UU.:** sin la Ley CLARITY, la clasificación de tokens como WLD (¿valor o materia prima?) sigue dependiendo de la interpretación de las agencias y de la administración de turno.
3. **Ejecución de World Money:** la app compite con monederos y neobancos consolidados, y su aporte al valor del token no está demostrado. Los datos de adopción de la app son un **dato no verificado** a la fecha de corte.
4. **Concentración en tesorerías corporativas:** que Eightco tenga 302 millones de WLD, ~8% del suministro circulante implícito según cálculo del analista, supone un riesgo de ventas grandes si esa empresa cambia de estrategia (Fuente de la tenencia: CoinMarketCap Top Stories, 2026-09).
5. **Divergencia entre plataformas:** las diferencias de hasta ~6% en el precio y ~6% en la capitalización entre CoinMarketCap y CoinGecko obligan a leer cualquier cifra puntual con cautela.
6. **Riesgo regulatorio biométrico y geopolítico:** no cambió en el mes, pero una sola decisión adversa (UE o Asia) puede modificar el escenario de forma abrupta.

## Fuentes consultadas

- CoinMarketCap: fichas de WLD, BTC, ETH, USDT, BNB, XRP, USDC, SOL, TRX, ZEC, HYPE, DOGE, ADA y BCH; métricas globales y de dominancia. https://coinmarketcap.com (recuperadas por búsqueda web el 2026-09-25)
- CoinMarketCap: "Latest Worldcoin News" (cmc-ai) y Top Stories "Worldcoin Surges 3.68% on World Money App Launch" / "Worldcoin Surges 11% on App Launch, Treasury News, Market Rally". https://coinmarketcap.com/cmc-ai/worldcoin-org/latest-updates/ (2026-09)
- CoinGecko: fichas de WLD, XRP, USDT, USDC, HYPE y DOGE. https://www.coingecko.com (recuperadas por búsqueda web el 2026-09-25)
- CoinDesk: página de precio de WLD. https://www.coindesk.com/price/worldcoin (2026-09-24)
- CoinDesk: "Crypto's biggest Senate push falls flat as the Clarity Act fails..." (2026-09-15); "Live updates: Clarity Act fails in Senate..." (2026-09-15); "The Fed rate decision is shaping up to be a nightmare for Warsh..." (2026-09-16); "Short squeeze drives bitcoin toward $85,000..." (2026-09-21); "Strategy resumes bitcoin purchases..." (2026-09-21); "BTC price recovers ... as falling oil price supports risk appetite" (2026-09-22); "Bitcoin nears $87,000, Zcash zooms 10% as U.S. bitcoin reserve bill clears committee" (2026-09-23); "Live updates: Bitcoin moves to $84,000, oil slides..." (2026-09-25); "Zcash jumps 20% to landmark $1,000 level" (2026-09-04); "Three years after MiCA became law..." (2026-07-02). https://www.coindesk.com
- The Block: "World launches 'World Money' super app..." (2026-09-17); "Bitcoin, ether swing after unanimous quarter-point Fed rate hike..." (2026-09-16); "'This one stings': Clarity Act fails procedural Senate vote" y "Clarity Act preliminary vote falls short..." (2026-09-15); "Bitcoin reclaims $80,000, Solana and Hyperliquid rally..." (2026-09-18); "Bitcoin taps $85,000 for first time since January..." (2026-09-21); "House committee moves to codify Trump's Strategic Bitcoin Reserve" (2026-09-16); "Grayscale's Zcash ETF plans 3-for-1 split..." (2026-09-18); "Hyperliquid open interest climbs to $14.3 billion..." (2026-09-08); "Bitcoin defies oil price spike..." (2026-09-01); "South Korea to start tokenizing 'all types' of securities..." (2026-09-04). https://www.theblock.co
- Decrypt: "Crypto Reacts: Bitcoin Slides as Clarity Act Fails to Clear Senate Vote" (2026-09-15); "House Committee Advances US Bitcoin Reserve Bill on Party-Line Split" (2026-09); "Worldcoin's WLD Jumps 8% on Grayscale ETF Filing" (2026-07). https://decrypt.co
- SEC / EDGAR: Grayscale Worldcoin ETF, Formulario S-1. https://www.sec.gov/Archives/edgar/data/2145351/000119312526308957/ck0002145351-20260720.htm (2026-07-20)
- ESMA: "Public Statement — ESMA calls on unauthorised crypto-asset service providers..." (fin del periodo transitorio de MiCA). https://www.esma.europa.eu (2026-06)
- World (documentación oficial): "Introducing World Money". https://world.org/blog/announcements/world-money (2026-09)
- Fichas previas del repositorio: `2026-08-30-wld-actualizacion.md` (precios de referencia del 25 al 30 de agosto) y `2026-07-17-wld-analisis.md`.

**Limitación metodológica declarada:** durante esta actualización el proxy de salida bloqueó el acceso directo a CoinMarketCap, CoinGecko (web y API), CoinDesk y The Block. Todas las cifras se obtuvieron de fragmentos de esas mismas fuentes recuperados por el buscador web el 2026-09-25, sin poder confirmar la hora exacta de cada dato "en vivo". Las variaciones frente a agosto usan como base cifras de fuentes secundarias documentadas en la ficha del 30-ago y deben leerse como aproximadas.

*Este documento es un análisis educativo y no constituye asesoría financiera profesional.*
