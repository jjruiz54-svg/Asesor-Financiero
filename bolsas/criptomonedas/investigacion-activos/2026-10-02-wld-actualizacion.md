# WLD — Worldcoin (Actualización 2026-10-02)

- **Bolsa / mercado:** Mercado global de criptomonedas (activo digital, red propia World Chain / Ethereum L2). No cotiza en ninguna bolsa tradicional de las cubiertas por este repositorio.
- **Fecha de análisis:** 2026-10-02
- **Fecha de corte de datos:** 2026-10-02. Las cifras de precio, capitalización y ranking provienen de fichas de CoinMarketCap, CoinGecko y CoinDesk **recuperadas por búsqueda web el 2026-10-02**. El acceso directo a CoinMarketCap.com y CoinDesk.com volvió a estar bloqueado por el proxy de salida del entorno (error `EGRESS_BLOCKED`), así que la hora exacta de cada cifra "en vivo" de CoinMarketCap y CoinGecko **no se pudo verificar**. Son coherentes con la sesión del 2 de octubre: el rango de 24h de BTC en CoinMarketCap (US$83.852,69–87.146,35) coincide con el máximo cerca de US$87.000 y la posterior caída por debajo de US$84.000 que reportó CoinDesk ese día. La única cifra con hora explícita es la de CoinDesk para WLD: 2026-10-02, 4:41 p. m. (hora del Este de EE. UU.).
- **Analista / agente:** Sub-agente `criptomonedas` (Claude Code)
- **Documentos relacionados:** `2026-07-17-wld-analisis.md` (ficha base completa), `2026-08-30-wld-actualizacion.md` y `2026-09-25-wld-actualizacion.md` (actualización anterior y **base de comparación** de este documento). Esta es una actualización puntual y no reemplaza la ficha base.

## Nota de cobertura obligatoria (regla del repositorio)

Se volvió a verificar el top 10 de criptomonedas por capitalización de mercado a la fecha de corte. **WLD no forma parte del top 10 por capitalización de mercado a la fecha de corte; se incluye de forma obligatoria por directriz del repositorio**, como posición 11.

*Glosario rápido:* la **capitalización de mercado** es el precio por las unidades en circulación. La **dominancia de Bitcoin** es la parte del valor total del mercado cripto que corresponde a BTC. Una **stablecoin** es un token diseñado para mantener un valor fijo, normalmente US$1. Una **liquidación** es el cierre forzado de una posición apalancada (comprada con dinero prestado) cuando el precio se mueve en su contra.

### Ranking top 10 vigente (CoinMarketCap, consulta por búsqueda web del 2026-10-02)

Base de comparación: precios de la ficha del 25-sep (CoinMarketCap, 2026-09-25). Las variaciones las calculó el analista: (precio 02-oct / precio 25-sep) − 1.

| Puesto (CMC) | Activo | Precio 02-oct (USD) | Cap. de mercado (USD) | Var. 24h | Precio base 25-sep (USD) | Var. desde 25-sep | Fuente / fecha |
|---|---|---|---|---|---|---|---|
| 1 | Bitcoin (BTC) | 84.544,70 | 1,699 billones (1.698.723 millones) | -0,20% | 84.184,47 | **+0,4%** | CoinMarketCap, 2026-10-02 |
| 2 | Ethereum (ETH) | 2.666,80 | 325.613 millones | -1,40% | 2.676,17 | **-0,4%** | CoinMarketCap, 2026-10-02 |
| 3 | Tether (USDT) | 0,999856 | 184.031 millones | dato no verificado | 0,9997 | Stablecoin; sin variación relevante | CoinMarketCap, 2026-10-02 |
| 4 | BNB | 769,95 | 102.525 millones | +0,19% | 778,62 | **-1,1%** | CoinMarketCap, 2026-10-02 |
| 5 | XRP | 1,50 | 94.578 millones | +0,12% | 1,58 | **-5,1%** (aprox.: ambos precios vienen redondeados a 2 decimales) | CoinMarketCap, 2026-10-02 |
| 6 | USD Coin (USDC) | 1,00 | 73.961 millones | 0,00% | Precio exacto no verificado el 25-sep | Stablecoin | CoinMarketCap, 2026-10-02 |
| 7 | Solana (SOL) | 122,50 | 72.040 millones | +3,94% | 114,86 | **+6,7%** | CoinMarketCap, 2026-10-02 |
| 8 | TRON (TRX) | 0,334827 | 31.801 millones | -0,76% | 0,3368 | **-0,6%** | CoinMarketCap, 2026-10-02 |
| 9 | Zcash (ZEC) | 1.322,46 | 22.340 millones | -6,83% | 1.549,71 | **-14,7%** | CoinMarketCap, 2026-10-02 |
| 10 | Hyperliquid (HYPE) | 88,19 | 22.137 millones | -1,26% | 93,67 | **-5,9%** | CoinMarketCap, 2026-10-02 |
| *(fuera: 11 en CMC)* | *Dogecoin (DOGE)* | *0,09326* | *16.027 millones* | *-1,58%* | *0,098487* | *-5,3%* | *CoinMarketCap, 2026-10-02* |
| **11 (obligatorio)** | **Worldcoin (WLD)** — puesto real #45 en CMC | **0,567593** | **2.153 millones** | **+9,34%** | **0,431836** | **+31,4%** | **CoinMarketCap, 2026-10-02** |

- **Composición sin cambios** frente al 25-sep: los mismos 10 activos y en el mismo orden. ZEC (#9) y HYPE (#10) están separados por solo ~US$200 millones de capitalización, así que su orden puede invertirse en cualquier momento (Fuente: CoinMarketCap, 2026-10-02).
- **Cap. total del mercado cripto:** ~US$2,97 billones, +0,5% en 24h; volumen 24h ~US$122.000 millones (Fuente: CoinGecko, 2026-10-02). En la ficha anterior se citó ~US$2,87 billones, pero esa cifra era de CoinMarketCap, así que la comparación entre ambas (+3,5%) es solo **indicativa**: mezcla plataformas.
- **Dominancia de Bitcoin:** 57,2% según CoinGecko (Fuente: CoinGecko, 2026-10-02). CoinDesk describió una dominancia que "se acerca a volver al 60%" y una cuota de USDT que bajó a ~6,3%, señal de que los traders pasan de "efectivo" (stablecoins) a tokens (Fuente: CoinDesk, 2026-10-02). La diferencia entre 57% y casi 60% se explica por la metodología de cada índice. La cifra de dominancia de CoinMarketCap al 02-oct es un **dato no verificado**, así que no se puede comparar con el 58,58% del 25-sep.
- **Advertencia de horas distintas:** cada cifra de CoinMarketCap se recuperó de una ficha distinta y puede corresponder a horas diferentes del día. Por ejemplo, CoinGecko mostraba ese día a BTC en US$86.831,98 (+3,50% en 24h), una foto tomada antes de la caída de la tarde (Fuente: CoinGecko, 2026-10-02), mientras que CoinMarketCap lo muestra en US$84.544,70, ya después de la caída. Las variaciones de una semana de BTC, ETH, BNB y TRX (todas por debajo de ±1,5%) son menores que esa diferencia intradía de ~2,7%, así que **deben leerse como "prácticamente sin cambio"**.

## Resumen ejecutivo

Al 2 de octubre de 2026, WLD cotiza en ~US$0,55–0,57 con una capitalización de ~US$2.135–2.153 millones, según la plataforma. Eso supone **+31,4% desde el 25-sep** (CoinMarketCap con CoinMarketCap), y WLD sube del puesto #50 al #45 en CoinMarketCap. Fue de lejos el mejor desempeño de la semana frente al top 10: BTC y ETH quedaron prácticamente planos, y ZEC cayó ~15%. El impulso de WLD fue sobre todo propio: una ruptura técnica el 27-sep y el renovado interés en la narrativa "identidad humana frente a la IA" tras el lanzamiento de World Money. A eso se sumó en los últimos días un viraje macro favorable al riesgo. La inflación PCE salió moderada (30-sep) y el empleo de septiembre fue muy débil (02-oct: +29.000 puestos), lo que redujo la probabilidad de otra subida de tasas de la Fed en octubre de ~70% a ~13–14%. WLD sigue fuera del top 10 y se incluye como posición 11 obligatoria.

## Datos clave

- **Puesto en el ranking:** #45 en CoinMarketCap (antes #50) y #53 en CoinGecko (antes #59) (Fuente: CoinMarketCap / CoinGecko, 2026-10-02). Está fuera del top 10 y se incluye como **posición 11 obligatoria**. Fecha de corte del ranking: 2026-10-02.
- **Precio (spot):** US$0,567593 (Fuente: CoinMarketCap, 2026-10-02); US$0,5619 (Fuente: CoinGecko, 2026-10-02); US$0,5463 a las 4:41 p. m. hora del Este (Fuente: CoinDesk, página de precio de WLD, 2026-10-02).
- **Rango 24h:** mínimo de US$0,4834 y máximo de US$0,5674 (Fuente: CoinMarketCap, 2026-10-02).
- **Capitalización de mercado:** US$2.153.309.163 (Fuente: CoinMarketCap, 2026-10-02); US$2.134.990.759 (Fuente: CoinGecko, 2026-10-02); US$2.070 millones (Fuente: CoinDesk, 2026-10-02).
- **Valoración totalmente diluida (FDV):** es la capitalización que tendría WLD si los 10.000 millones de tokens del suministro máximo estuvieran ya en circulación. Es de US$5.628 millones (Fuente: CoinGecko, 2026-10-02) y de US$5.460 millones (Fuente: CoinDesk, 2026-10-02). Hoy circula ~38% del suministro máximo (cálculo del analista: 3.794 / 10.000 millones).
- **Volumen 24h:** US$517.362.670 (Fuente: CoinMarketCap, 2026-10-02); US$517.242.713 (Fuente: CoinGecko, 2026-10-02); US$390,51 millones (Fuente: CoinDesk, 2026-10-02). El volumen de CMC aumentó ~51% frente a los US$342,7 millones del 25-sep (cálculo del analista).
- **Variación 24h:** +9,34% (Fuente: CoinMarketCap, 2026-10-02); +13,40% (Fuente: CoinGecko, 2026-10-02); +9,10% (Fuente: CoinDesk, 2026-10-02).
- **Variación 7 días:** +22,0%, frente a +2,0% de BTC en el mismo periodo (Fuente: CoinGecko, 2026-10-02).
- **Suministro circulante:** 3.793.755.654 WLD (Fuente: CoinMarketCap, 2026-10-02). Es ~+3,9% más que los ~3.652 millones implícitos del 25-sep (cálculo del analista). **Advertencia:** ese salto, en una sola semana, es mucho mayor que la dilución mensual de ~0,9% observada entre agosto y septiembre. Puede reflejar un desbloqueo de tokens o un ajuste de metodología de CoinMarketCap. La causa es un **dato no verificado**.
- **Máximo y mínimo históricos (según CoinMarketCap):** ATH de US$11,82 (10-mar-2024), con el precio actual un 95,2% por debajo; ATL de US$0,2279 (17-may-2026), con el precio actual un 148,98% por encima (Fuente: CoinMarketCap, 2026-10-02). *Nota:* CoinGecko registraba ATH de US$11,74 y ATL de US$0,2300 (Fuente: CoinGecko, 2026-09-25). Las diferencias se deben a la agregación de precios de cada plataforma.
- **Dividendos / múltiplos:** no aplican. WLD es un token y no reparte dividendos ni tiene utilidades por acción.

## Variación desde el 25 de septiembre de 2026 (fecha de corte de la actualización anterior)

| Métrica | 25-sep-2026 | 02-oct-2026 | Variación |
|---|---|---|---|
| Precio CoinMarketCap | US$0,431836 (CMC, 2026-09-25) | US$0,567593 (CMC, 2026-10-02) | **+31,4%** |
| Precio CoinGecko | US$0,4569 (CoinGecko, 2026-09-25) | US$0,5619 (CoinGecko, 2026-10-02) | +23,0% |
| Precio CoinDesk | US$0,41 (CoinDesk, 2026-09-24) | US$0,5463 (CoinDesk, 2026-10-02, 16:41 ET) | +33,2% (la base es del 24-sep) |
| Cap. CoinMarketCap | US$1.577,0 millones (CMC, 2026-09-25) | US$2.153,3 millones (CMC, 2026-10-02) | +36,5% |
| Cap. CoinGecko | US$1.668,4 millones (CoinGecko, 2026-09-25) | US$2.135,0 millones (CoinGecko, 2026-10-02) | +28,0% |
| Puesto CMC / CoinGecko | #50 / #59 | #45 / #53 | Sube 5 / 6 puestos |
| Suministro circulante | ~3.652 millones (implícito, CMC, 2026-09-25) | 3.793,8 millones (CMC, 2026-10-02) | ~+3,9% (dilución; causa no verificada) |

Las variaciones las calculó el analista con las cifras citadas. Las tres plataformas coinciden en una subida de entre **+23% y +33%** en una semana. La dispersión se explica por la hora de consulta (el 25-sep CoinGecko ya iba +12,5% intradía) y por la metodología. La capitalización creció más que el precio (+36,5% frente a +31,4% en CMC) por el aumento del suministro: es la **dilución**, que reparte el valor entre más tokens.

**Comparación con el mercado (misma fuente, CMC):** WLD +31,4%; SOL +6,7%; BTC +0,4%; ETH -0,4%; HYPE -5,9%; ZEC -14,7%. WLD superó con claridad a todos los integrantes del top 10.

## Comportamiento histórico (resumen)

WLD se lanzó el 24 de julio de 2023, así que su **historial disponible empieza en esa fecha y es inferior a la ventana mínima de 5 años**. El detalle histórico está en la ficha base `2026-07-17-wld-analisis.md`. En resumen, pasó de un ATH de US$11,82 (10-mar-2024) a un ATL de US$0,2279 (17-may-2026), y desde ese mínimo el precio casi se ha multiplicado por 2,5 (+148,98%) (Fuente: CoinMarketCap, 2026-10-02). Recorrido en las fichas del repositorio: US$0,378 (30-ago) → US$0,432 (25-sep) → US$0,568 (02-oct), todo en CoinMarketCap.

## Eventos relevantes desde el 25 de septiembre de 2026

### Hechos específicos de WLD / World

1. **Ruptura técnica del 27-sep.** WLD subió 9,08% hasta US$0,525 en 24 horas, frente a +0,65% de Bitcoin. CoinMarketCap lo atribuyó a la ruptura de un rango lateral con volumen alto (3,6 desviaciones estándar sobre lo normal), al resurgir de la narrativa de World como "capa de identidad" en la era de la IA tras el lanzamiento de World Money, y a un rendimiento de +12,48% frente a BTC. Señaló US$0,5056 como nivel técnico de referencia (Fuente: CoinMarketCap, Top Stories "Worldcoin Surges 8.36% on AI Hype, Altcoin Rally, Breakout" y CMC AI Price Analysis, 2026-09-27). *El análisis técnico es una lectura de patrones de precio y volumen, no un dato fundamental.*
2. **Nueva subida del 02-oct.** +9,10% en 24h hasta US$0,5463, con un volumen de US$390,51 millones (Fuente: CoinDesk, 2026-10-02). En las fuentes de confianza no se encontró un catalizador específico de WLD para ese día. Coincide con el giro del mercado hacia el riesgo tras el dato de empleo (ver evento 6), pero esa relación es una **interpretación del analista**, no un hecho verificado.
3. **Volatilidad previa (24-sep).** En la madrugada del 24-sep WLD cayó un 11% y provocó ~US$4,36 millones en liquidaciones de posiciones apalancadas (Fuente: CoinMarketCap, "Latest Worldcoin News", 2026-09). Muestra la fuerte presencia de apalancamiento en el token.
4. **Derivados regulados en EE. UU.** Kalshi, un mercado regulado por la CFTC, lista futuros perpetuos (contratos sin fecha de vencimiento) sobre WLD. Según CoinMarketCap, el anuncio provocó un repunte de ~7% (Fuente: CoinMarketCap, "Latest Worldcoin News", 2026-09). La fecha exacta del listado es un **dato no verificado**: probablemente anterior al 25-sep.
5. **ETF de Grayscale sobre WLD (GWLD): sigue pendiente.** El S-1 indica que las acciones se listarían en Nasdaq bajo la regla 5711(d), es decir, bajo los **estándares genéricos de listado**, que permiten listar sin un trámite individual 19b-4 ante la SEC. No empezarían a cotizar hasta que Nasdaq confirme que cumplen los requisitos (Fuente: SEC EDGAR, S-1 de Grayscale Worldcoin ETF, 2026-07-20). A la fecha de corte **no se encontró evidencia de lanzamiento**: su estado es un dato no verificado.
6. **Frente regulatorio biométrico:** en CoinDesk, The Block y Decrypt no apareció ninguna nueva prohibición ni sanción contra World entre el 25-sep y el 02-oct-2026. Siguen vigentes las restricciones ya documentadas (Hong Kong, España, Brasil, Kenia, Corea del Sur, entre otras).

### Hechos de mercado, macro y regulación que afectaron a todo el sector

7. **Dato de empleo muy débil en EE. UU. (02-oct).** La economía creó solo 29.000 empleos en septiembre, frente a 84.000–93.000 que esperaba QCP, y el desempleo subió de 4,1% a 4,2% (Fuente: The Block, 2026-10-02). Además hubo revisiones a la baja de julio y agosto (Fuente: Decrypt, 2026-10-02). BTC tocó ~US$87.000 tras el dato, devolvió unos US$2.000 en poco tiempo y luego bajó de US$84.000. Hubo cerca de US$600 millones en liquidaciones (Fuente: CoinDesk, 2026-10-02). CoinDesk lo registró en US$84.549,32 a las 7:06 p. m. ET (Fuente: CoinDesk, 2026-10-02).
8. **Fed: caen las apuestas de otra subida en octubre.** La probabilidad de una subida en octubre bajó de ~70% a principios de semana a ~30% tras discursos moderados (*dovish*) y a ~13–14% tras el dato de empleo (Fuente: CoinDesk, 2026-10-02; Decrypt, 2026-10-02). John Williams, presidente de la Fed de Nueva York, dijo que "no hay urgencia" tras la subida de septiembre y que su escenario base es una sola subida más este año. El vicepresidente de la Fed, Philip Jefferson, dijo que la decisión "puede tomar más tiempo" (Fuente: Decrypt, 2026-10-02).
9. **Inflación PCE moderada (30-sep).** Es el índice de precios que la Fed usa como referencia. En agosto, la PCE general subió 0,3% mensual y 3,4% anual, y la subyacente (sin alimentos ni energía) 0,2% mensual y 3,0% anual (Fuente: The Block, 2026-09-30). The Block lo interpretó como un dato que enfría las apuestas de subida en octubre.
10. **Rendimientos de los bonos, un freno.** El rendimiento del Tesoro de EE. UU. a 10 años bajó 9,4 puntos básicos, hasta 5,217%, el 01-oct (Fuente: CoinDesk, 2026-10-01). Aun así sigue en niveles altos, y tanto CoinDesk como The Block los señalan como un viento en contra para los activos de riesgo (Fuente: CoinDesk, 2026-10-02; The Block, 2026-09-30).
11. **Cierre del tercer trimestre.** BTC subió 42,7% en el 3T-2026, su mejor trimestre desde el 1T-2024, y ETH subió 70,8%, su mejor trimestre desde el 1T-2021 (Fuente: CoinDesk, 2026-10-01).
12. **Flujos a ETF spot.** Los ETF spot de bitcoin en EE. UU. captaron US$2.650 millones netos en septiembre (US$3.520 millones en agosto) y los de ether US$832,43 millones (Fuente: The Block, 2026-10-02). En la semana al 26-sep, los ETF de bitcoin sumaron US$2.400 millones y quedaron en positivo para 2026 (Fuente: The Block, 2026-09-26). El 1 de octubre entraron US$103 millones (Fuente: CoinDesk, 2026-10-02).
13. **SEC: propuesta de regla de custodia cripto (01-oct).** La SEC propuso una regla que aclara quién puede custodiar los criptoactivos de los clientes de asesores y fondos. Permite la autocustodia por el asesor en casos limitados (cuando no encuentre un custodio calificado) y acepta fideicomisos con licencia estatal como custodios. Tiene 60 días de comentarios públicos (Fuente: CoinDesk, 2026-10-01; The Block, 2026-10-01). Es parte de la vía administrativa que la SEC y la CFTC aceleraron tras el fracaso de la Ley CLARITY: la exención de innovación de la SEC y la pre-regla de la CFTC enviada a la Casa Blanca (OIRA) (Fuente: CoinDesk, 2026-09-18; The Block, 2026-09-16).
14. **Hackeo de Bitget (24–26-sep).** El exchange Bitget sufrió un robo inicialmente cifrado en US$351,6 millones y luego en US$387,5 millones. El atacante comprometió un sistema interno de sus monederos y falsificó datos de transacciones. No se comprometieron llaves privadas (Fuente: CoinDesk, 2026-09-25; The Block, 2026-09-26). La directora ejecutiva dijo que el ataque es coherente con grupos de hackers de **Corea del Norte**, aunque la atribución no es definitiva (Fuente: Decrypt, 2026-09). Circle y Tether congelaron la billetera del atacante (Fuente: CoinDesk, 2026-09-25). Bitget cubre la pérdida con su fondo de protección de más de US$464 millones (Fuente: Decrypt, 2026-09). El mercado "se lo sacudió" con un rally de altcoins ese mismo día (Fuente: CoinDesk, 2026-09-25).
15. **Corrección de Zcash.** ZEC cayó ~21% desde su pico de US$1.698 por salidas del ETF de Grayscale (US$30,25 millones el 30-sep, frente a US$268 millones de entradas acumuladas) y por sospechas de que fondos robados de origen norcoreano pasaron por su "pool blindado" de privacidad (Fuente: Decrypt, 2026-10). La fecha exacta de publicación es un dato no verificado. Esto explica el -14,7% semanal de ZEC en la tabla.

## Contexto geopolítico y macroeconómico

**Hechos:**

- **Política monetaria de EE. UU.:** el rango de fondos federales sigue en 3,75–4,00% tras la subida del 16-sep (Fuente: The Block, 2026-09-16). La semana trajo datos que restan presión para otra subida: PCE moderada y empleo débil. Las apuestas de una subida en octubre cayeron a ~13–14% (Fuente: CoinDesk / Decrypt, 2026-10-02). Para los activos de riesgo, menos subidas de tasas suelen ser una buena noticia. El contrapeso son los rendimientos de largo plazo, que siguen altos (10 años en ~5,2%) (Fuente: CoinDesk, 2026-10-01).
- **Corea del Norte, ciberseguridad y sanciones:** el hackeo de Bitget, atribuido de forma preliminar a grupos norcoreanos (Fuente: Decrypt, 2026-09), conecta el mercado cripto con el régimen de sanciones internacionales. Que dos emisores de stablecoins (Circle y Tether) congelaran fondos muestra que las stablecoins centralizadas funcionan en la práctica como un punto de control frente a actores sancionados (Fuente: CoinDesk, 2026-09-25). Para monedas de privacidad como ZEC, el uso por actores sancionados es un riesgo regulatorio directo (Fuente: Decrypt, 2026-10).
- **Regulación en EE. UU. (SEC / CFTC):** sin la Ley CLARITY, la regulación avanza por la vía administrativa (ver evento 13). Lo positivo es que da más claridad para la custodia institucional. Lo negativo es que puede revertirse con un cambio de administración, porque no es ley.
- **Adopción institucional:** los flujos a ETF spot de BTC y ETH siguieron siendo positivos en septiembre (Fuente: The Block, 2026-10-02). Citi revisó su objetivo de precio de BTC a US$113.000 (Fuente: The Block, 2026-10-02). Ese objetivo es la **opinión de un tercero**, no un dato.
- **Unión Europea (MiCA):** no se encontraron novedades entre el 25-sep y el 02-oct. Sigue vigente lo documentado: el periodo transitorio de MiCA terminó el 1 de julio de 2026 (Fuente: ESMA, declaración pública de junio de 2026). Para World, la supervisión de los datos biométricos depende del RGPD.
- **Asia:** en las fuentes de confianza no se encontraron cambios regulatorios nuevos en China, Hong Kong, Japón, Singapur o Corea del Sur entre el 25-sep y el 02-oct-2026 que afecten directamente a WLD: dato no verificado. Sigue vigente el plan de tokenización de valores de Corea del Sur desde 2027 (Fuente: The Block, 2026-09-04).

**Opinión del analista (no es un dato verificado):** la semana muestra una **desconexión** entre WLD y el mercado. Los grandes del top 10 quedaron planos o en rojo, mientras WLD subió más de 30%. Cuando un activo pequeño sube tanto sin una noticia fundamental nueva y con volumen y apalancamiento al alza (ruptura técnica, futuros perpetuos, liquidaciones del 24-sep), la subida suele ser frágil y las correcciones, bruscas. El macro (Fed menos agresiva) es un viento a favor, pero los bonos a 10 años por encima de 5% limitan el entusiasmo. Para el lector colombiano, una Fed menos agresiva tiende a debilitar algo el dólar, lo que reduce el costo en pesos de comprar activos dolarizados. Ese efecto cambiario no se cuantifica aquí: dato no verificado.

## Escenarios

*Estas proyecciones son opinión del analista y un ejercicio de escenarios, no datos verificados ni asesoría financiera. Actualizan los escenarios de la ficha del 25-sep.*

- **Alcista:** WLD se sostiene por encima de ~US$0,50 (la zona de ruptura señalada por CMC), la Fed no sube en octubre y el ETF de Grayscale (GWLD) logra listarse por la vía de estándares genéricos. En ese caso podría buscar la zona de US$0,60–0,80 en el cuarto trimestre. *Cambio frente al 25-sep:* el precio ya entró en la parte baja del antiguo rango alcista (US$0,60–1,00), así que el rango se ajusta.
- **Base:** tras una subida de +31% en una semana, lo más probable es una consolidación con retrocesos parciales, en un rango de ~US$0,45–0,62. La dilución, que esta semana parece acelerada, actúa como freno.
- **Bajista:** se cierran las posiciones apalancadas acumuladas, el mercado vuelve a temer la inflación (rendimientos al alza) o aparece una sanción biométrica nueva. WLD podría devolver toda la subida de la semana y volver a ~US$0,40–0,43, el nivel del 25-sep. Un escenario extremo lo llevaría de vuelta a ~US$0,30.

## Riesgos

*Riesgos identificados para fines educativos; no constituyen recomendación. Siguen vigentes los riesgos de la ficha base y de la actualización anterior: datos biométricos, dilución, concentración de la gobernanza y de las tesorerías corporativas (Eightco, 302 millones de WLD), baja liquidez relativa y riesgo narrativo.*

1. **Sobre-extensión y apalancamiento:** +31% en una semana, con futuros perpetuos disponibles y un precedente de liquidaciones (24-sep, -11%), deja a WLD expuesto a caídas bruscas (Fuente del precedente: CoinMarketCap, 2026-09).
2. **Dilución acelerada no explicada:** el suministro circulante aumentó ~3,9% en una semana según CMC (cálculo del analista), mientras que la FDV (US$5.628 millones) más que duplica la capitalización actual (Fuente: CoinGecko, 2026-10-02). Si es un desbloqueo, puede añadir presión vendedora.
3. **Macro: rendimientos de largo plazo:** aunque baje la probabilidad de subidas de la Fed, un 10 años por encima de 5% encarece el capital y compite con los activos especulativos (Fuente: CoinDesk, 2026-10-01).
4. **Seguridad y sanciones:** hackeos como el de Bitget (US$387,5 millones), atribuidos a actores estatales sancionados, pueden provocar respuestas regulatorias más duras para todo el sector (Fuente: The Block, 2026-09-26).
5. **Vacío legislativo en EE. UU.:** las reglas administrativas de la SEC y la CFTC no tienen la estabilidad de una ley. La clasificación de tokens como WLD sigue sujeta a cambios de administración.
6. **Divergencia entre plataformas:** las diferencias de hasta ~4% en el precio del mismo día entre CoinMarketCap (US$0,5676), CoinGecko (US$0,5619) y CoinDesk (US$0,5463) obligan a leer cualquier cifra puntual con cautela (Fuente: CMC / CoinGecko / CoinDesk, 2026-10-02).

## Fuentes consultadas

- CoinMarketCap: fichas de WLD, BTC, ETH, USDT, BNB, XRP, USDC, SOL, TRX, ZEC, HYPE y DOGE. https://coinmarketcap.com (recuperadas por búsqueda web el 2026-10-02)
- CoinMarketCap: Top Stories "Worldcoin Surges 8.36% on AI Hype, Altcoin Rally, Breakout" (2026-09-27), https://coinmarketcap.com/top-stories/6ab93e939b4b0f5973711366/ ; CMC AI "Latest Worldcoin (WLD) Price Analysis", https://coinmarketcap.com/cmc-ai/worldcoin-org/price-analysis/ ; "Latest Worldcoin News", https://coinmarketcap.com/cmc-ai/worldcoin-org/latest-updates/ (2026-09)
- CoinGecko: fichas de WLD y BTC; gráficos de capitalización global. https://www.coingecko.com/en/coins/worldcoin ; https://www.coingecko.com/en/charts (recuperadas por búsqueda web el 2026-10-02)
- CoinDesk: página de precio de WLD (2026-10-02, 16:41 ET), https://www.coindesk.com/price/worldcoin ; página de precio de BTC (2026-10-02, 19:06 ET), https://www.coindesk.com/price/bitcoin ; "Live updates: Bitcoin reverses big early gains following soft U.S. jobs data" (2026-10-02); "Crypto traders are in risk-on mode as bitcoin (BTC) dominance nears return to 60%" (2026-10-02); "Bitcoin edges higher ahead of U.S. jobs report as global bond yields surge" (2026-10-02); "Live updates: Bitcoin posts tentative gains as rates drop ahead of Friday's jobs report" (2026-10-01); "SEC maps out crypto custody in new proposal..." (2026-10-01); "CFTC sends crypto rules to White House to review..." (2026-09-18); "Crypto shrugs off Bitget's $351.6 million hack as altcoins rally" (2026-09-25); "Circle and Tether step in to freeze hacker wallet..." (2026-09-25); "Bitget's $352 million hack happened via spoofed transfers..." (2026-09-25). https://www.coindesk.com
- The Block: "Bitcoin nears highest level since January as $85,000 sell wall clears, US jobs data disappoints" (2026-10-02); "Spot bitcoin ETFs log $2.7 billion in September inflows..." (2026-10-02); "SEC proposes framework allowing investment advisers, funds to self-custody crypto" (2026-10-01); "Bitcoin steadies as soft PCE cools October Fed rate hike bets" (2026-09-30); "Bitcoin ETFs turn positive for 2026 with $2.4 billion weekly inflow..." (2026-09-26); "The Daily: Bitget hit by $387.5 million security breach" (2026-09-26); "'Go time': SEC, CFTC prepare to push crypto rules as Clarity Act stalls in Senate" (2026-09-16). https://www.theblock.co
- Decrypt: "Bitcoin Heads Higher on Macro Moves: Where Does BTC Go Next?" (2026-10-02), https://decrypt.co/379936 ; "'Uptober' Off With a Bang as Bitcoin Surges to $86K" (2026-10), https://decrypt.co/379932 ; "Zcash Drops 21% From Recent High..." (2026-10), https://decrypt.co/379901 ; "Bitget Hack Losses Climb to $387M..." (2026-09), https://decrypt.co/379350
- SEC / EDGAR: Grayscale Worldcoin ETF, Formulario S-1. https://www.sec.gov/Archives/edgar/data/2145351/000119312526308957/ck0002145351-20260720.htm (2026-07-20)
- ESMA: declaración pública sobre el fin del periodo transitorio de MiCA (2026-06), https://www.esma.europa.eu
- Fichas previas del repositorio: `2026-09-25-wld-actualizacion.md` (precios base del 25-sep), `2026-08-30-wld-actualizacion.md` y `2026-07-17-wld-analisis.md`.

**Limitación metodológica declarada:** durante esta actualización el proxy de salida bloqueó el acceso directo a CoinMarketCap y CoinDesk. Todas las cifras se obtuvieron de fragmentos de las fuentes de confianza recuperados por el buscador web el 2026-10-02, sin poder confirmar la hora exacta de cada dato "en vivo" de CoinMarketCap y CoinGecko. Las variaciones de una semana de los activos del top 10 son del mismo orden que la volatilidad intradía del 02-oct, así que solo las de WLD (+31%), ZEC (-15%) y SOL (+7%) son claramente distinguibles del ruido.

*Este documento es un análisis educativo y no constituye asesoría financiera profesional.*
