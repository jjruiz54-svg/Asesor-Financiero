# WLD — Worldcoin

- **Bolsa / mercado:** Mercado global de criptomonedas (activo digital, red propia World Chain / Ethereum L2). No cotiza en ninguna bolsa tradicional de las cubiertas por este repositorio.
- **Fecha de análisis:** 2026-07-17
- **Fecha de corte de datos:** 2026-07-17 (las cifras de mercado individuales citan su propia fecha puntual de consulta, mayoritariamente entre el 2026-07-11 y el 2026-07-16, dado que los datos de precio cripto cambian por minuto)
- **Analista / agente:** Sub-agente `criptomonedas` (Claude Code)

## Nota de cobertura obligatoria (regla del repositorio)

Antes de analizar WLD, se determinó el top 10 de criptomonedas por capitalización de mercado vigente. **WLD no forma parte del top 10 por capitalización de mercado a la fecha de corte; se incluye de forma obligatoria por directriz del repositorio**, como posición 11.

**Ranking top 10 vigente (compilado de datos de CoinMarketCap y CoinGecko, consulta 2026-07-11 a 2026-07-16):**

| Puesto | Activo | Cap. de mercado aprox. | Fuente / fecha |
|---|---|---|---|
| 1 | Bitcoin (BTC) | ~1,28–1,29 billones USD (precio ~US$63.910) | CoinMarketCap, 2026-07-16 |
| 2 | Ethereum (ETH) | ~222.330 millones USD (precio ~US$1.872) | CoinMarketCap, 2026-07-16 |
| 3 | Tether (USDT) | ~184.100 millones USD | CoinMarketCap, 2026-07-16 |
| 4 | BNB | ~75.510 millones USD | CoinMarketCap, 2026-07-16 |
| 5 | USD Coin (USDC) | ~73.270 millones USD | CoinMarketCap, 2026-07-14 |
| 6 | XRP | ~67.950 millones USD (precio ~US$1,10) | CoinMarketCap, 2026-07-16 |
| 7 | Solana (SOL) | ~43.700 millones USD (precio ~US$75,83) | CoinMarketCap, 2026-07-14 |
| 8 | TRON (TRX) | ~30.600–31.350 millones USD (precio ~US$0,32) | CoinMarketCap, 2026-07-11 |
| 9 | Hyperliquid (HYPE) | ~15.100 millones USD (precio ~US$59,95) | CoinGecko, 2026-07-medio julio |
| 10 | Dogecoin (DOGE) | ~11.200–12.300 millones USD | CoinMarketCap, 2026-07-medio julio |
| **11 (obligatorio)** | **Worldcoin (WLD)** | **~1.350–1.430 millones USD (rank #48 CMC / #55 CoinGecko)** | **CoinMarketCap / CoinGecko, 2026-07-15/16** |

*Nota metodológica:* el acceso directo en vivo a CoinMarketCap.com y CoinGecko.com estuvo bloqueado durante esta investigación (error HTTP 403 del proxy de salida), por lo que el ranking se reconstruyó cruzando múltiples citas textuales de esas mismas plataformas recuperadas por búsqueda web en fechas distintas dentro de la ventana 2026-07-11 a 2026-07-16. El orden de las posiciones 8 a 10 fluctúa levemente entre CoinMarketCap y CoinGecko (HYPE y DOGE intercambian posición según la plataforma y el momento); esto no afecta la conclusión de que **WLD queda muy por debajo del top 10** en cualquiera de las dos plataformas.

## Resumen ejecutivo

Worldcoin (WLD) es el token nativo de World (antes "Worldcoin"), el proyecto de identidad digital biométrica cofundado por Sam Altman (también CEO de OpenAI) y desarrollado por la empresa privada Tools for Humanity (TFH). Su propuesta central es "World ID": un sistema de verificación de humanidad ("proof of human") mediante escaneo de iris con un dispositivo llamado Orb, pensado para distinguir personas reales de bots e IA en internet. Lanzado el 24 de julio de 2023, el token ha tenido una trayectoria extremadamente volátil: de un máximo histórico de US$11,74 en marzo de 2024 cayó a un mínimo histórico de aproximadamente US$0,23 en mayo de 2026, cotizando alrededor de US$0,41 a mediados de julio de 2026. El proyecto combina fuerte respaldo de capital de riesgo y una narrativa ligada al auge de la inteligencia artificial, con una presión bajista estructural por la emisión constante de nuevos tokens y una cadena de prohibiciones regulatorias en varios países por el manejo de datos biométricos.

## Datos clave

- **Precio (spot):** ~US$0,41 (Fuente: MetaMask/CoinGecko, agregando datos de mercado, 2026-07-15)
- **Capitalización de mercado:** ~US$1.350–1.430 millones (varía según plataforma: ~US$1.354 millones en CoinMarketCap, ~US$1.357–1.434 millones en CoinGecko) (Fuente: CoinMarketCap / CoinGecko, 2026-07-15/16)
- **Puesto en el ranking:** #48 en CoinMarketCap, #55 en CoinGecko (Fuente: CoinMarketCap / CoinGecko, 2026-07-15/16) — **fuera del top 10**, incluida como posición 11 obligatoria según la regla de cobertura del repositorio.
- **Volumen 24h:** entre ~US$71,7 millones y ~US$210 millones según la plataforma y el momento del día (Fuente: WorldCoinIndex 2026-07-17; CoinDesk 2026-07-16; CoinMarketCap 2026-07-11)
- **Suministro circulante:** ~3.500 millones de WLD (Fuente: agregadores de mercado citando CoinGecko/CoinMarketCap, 2026-07)
- **Suministro total/máximo:** 10.000 millones de WLD (tope fijo del protocolo) (Fuente: World Foundation, documentación oficial "The Circulating Supply of Worldcoin (WLD): An Explainer", world.org)
- **Máximo histórico (ATH):** US$11,74, alcanzado el 10 de marzo de 2024 (Fuente: agregadores de precio citando CoinGecko/CoinMarketCap)
- **Mínimo histórico (ATL):** ~US$0,228–0,230, alcanzado el 18 de mayo de 2026 (Fuente: agregadores de precio citando CoinGecko/CoinMarketCap)

## Comportamiento desde el lanzamiento (historial completo, inferior a 5 años)

**Historial disponible desde el 24 de julio de 2023, inferior a la ventana mínima de 5 años exigida por la plantilla estándar del repositorio.** WLD tiene, a la fecha de este análisis, poco menos de 3 años de historia de mercado.

- **24 de julio de 2023 — lanzamiento:** el token debutó cotizando alrededor de US$2,20 tras casi tres años de desarrollo del proyecto, listándose de inmediato en exchanges importantes como Binance (Fuente: cobertura de prensa cripto agregada sobre el lanzamiento, 2023-07-24).
- **Cierre de 2023 / inicio de 2024:** el precio subió hasta aproximadamente US$3,68 al cierre del año, en medio del primer repunte especulativo del token.
- **2024 — año de máximos y fuerte reversión:** WLD alcanzó su máximo histórico de US$11,74 el 10 de marzo de 2024, impulsado por el hype de IA y la expectativa de "World Chain". Tras el pico, el precio cayó por debajo de US$5 en abril de 2024 y osciló entre US$1,64 y US$4,10 entre junio y octubre de 2024. El año cerró en torno a US$2,09–2,15, es decir, con una caída aproximada de 40-45% desde el nivel de inicio de año (~US$3,68), pese a haber tocado un máximo casi 6 veces superior a mitad de año.
- **2025 — año bajista:** descrito por analistas de mercado como el peor año de WLD hasta la fecha; el precio pasó de ~US$2,09 a comienzos de año a un cierre de ~US$0,268, con un precio promedio anual de ~US$1,08. En abril de 2025 llegó a caer a ~US$0,76 antes de un rebote parcial; en el segundo semestre marcó nuevos mínimos históricos.
- **2026 (año en curso, hasta el 17 de julio):** el token marcó un nuevo mínimo histórico de ~US$0,228–0,230 el 18 de mayo de 2026, para luego recuperarse hasta ~US$0,41 a mediados de julio de 2026 — un repunte aproximado de +75-80% desde ese mínimo, aunque todavía muy por debajo de los niveles de 2024.

**Rendimiento anual aproximado (cifras redondeadas, no auditadas de forma independiente, compiladas de agregadores de precio de mercado):**

| Año | Variación aproximada |
|---|---|
| 2023 (parcial, desde el 24 jul.) | +67% aprox. (de ~US$2,20 a ~US$3,68) |
| 2024 | entre -40% y -45% (de ~US$3,68 a ~US$2,09–2,15), con un pico intermedio de +220% sobre el ATH de marzo |
| 2025 | entre -85% y -87% (de ~US$2,09 a ~US$0,268) |
| 2026 (YTD al 17 jul.) | aprox. +50-55% (de ~US$0,268 a ~US$0,41) |

**Eventos de precio más relevantes del período:**
- Lanzamiento del token y salida a exchanges (24 jul. 2023).
- Rally previo al lanzamiento de World Chain y ATH de marzo 2024, coincidente con el auge narrativo de "criptomonedas + IA".
- Migración/lanzamiento de la red propia World Chain en octubre de 2024, sin que el evento evitara la posterior caída de precio.
- Presión de venta sostenida por el calendario de desbloqueo de tokens (emisión diaria) durante 2024-2025.
- Nuevo mínimo histórico en mayo de 2026, seguido de recuperación parcial ligada al recorte del ritmo de emisión anunciado para el 24 de julio de 2026.

## Contexto técnico y fundamental del proyecto

- **World ID:** sistema de verificación biométrica de "prueba de humanidad" mediante escaneo de iris con el dispositivo Orb. En 2026 la Worldcoin Foundation lanzó una actualización de "World ID full-stack" que integra el sistema con socios externos (por ejemplo, funciones ligadas a Tinder, Zoom y herramientas de firma/ticketing), ampliando el uso del World ID más allá del propio ecosistema cripto (Fuente: The Block, cobertura de anuncios de World, 2026).
- **World Chain:** red Layer-2 de Worldcoin construida sobre el OP Stack de Optimism (Superchain), presentada en abril de 2024 y con mainnet lanzada en octubre de 2024, coincidiendo con el cambio de marca de "Worldcoin" a "World Network" / "World" (Fuente: CoinDesk, "Worldcoin, Sam Altman's Crypto Project, Is Building a Layer-2 Chain", 2024-04-17; Decrypt, "Why Worldcoin Built an Ethereum Network Specifically for Humans", 2024).
- **Tokenomics y emisión:** suministro máximo fijo de 10.000 millones de WLD, distribuido entre la comunidad (la mayor parte, reclamable por usuarios verificados con el tiempo), inversores de TFH, el equipo de desarrollo inicial y una reserva de TFH, con un calendario de desbloqueo que se extiende hasta 2038 (Fuente: documentación oficial, World Whitepaper — Tokenomics, whitepaper.world.org). A partir del 24 de julio de 2026 la emisión diaria de tokens se reduce en aproximadamente 43%, de ~5,1 millones a ~2,9 millones de WLD diarios, afectando tanto las asignaciones comunitarias como las de equipo/inversores (Fuente: cobertura de mercado citando datos de la Worldcoin Foundation, julio de 2026). No se encontró documentación oficial que describa un mecanismo de quema (burn) de tokens; el control de la oferty circulante se basa en el calendario de vesting/emisión, no en destrucción de tokens.
- **Gobernanza:** el proyecto es gestionado por la World Foundation, una fundación "sin miembros" (memberless), constituida en las Islas Caimán, gobernada por un consejo de 4 directores. El marco fundacional contempla un mecanismo de gobernanza tipo DAO mediante el cual la comunidad puede emitir recomendaciones vinculantes al consejo directivo, sujetas a los deberes fiduciarios de los directores (Fuente: World Foundation, foundation.world.org; The Block, cobertura del cambio de marca y gobernanza, octubre de 2024).
- **Sam Altman y Tools for Humanity:** Sam Altman, CEO de OpenAI, es cofundador del proyecto; Tools for Humanity (TFH) es la empresa privada que desarrolla la tecnología. TFH ha levantado capital en varias rondas: US$100 millones en marzo de 2022 a una valuación de US$3.000 millones, y una Serie C de US$115 millones en mayo de 2023 liderada por Blockchain Capital con participación de a16z, Bain Capital Crypto y Distributed Global (Fuente: CoinDesk, "Sam Altman's Crypto Project Worldcoin Raises $115M, Led by Blockchain Capital", 2023-05-25). Más recientemente, World recaudó US$135 millones adicionales mediante una venta de tokens WLD para financiar su expansión en Estados Unidos (Fuente: The Block, "World raises $135 million via WLD token sale to expand across the US"). En junio de 2026, mientras OpenAI presentaba de forma confidencial su solicitud de salida a bolsa (IPO), se reportó que Tools for Humanity —valorada en unos US$2.500 millones— realizaba recortes de personal en medio de dificultades para generar ingresos (Fuente: cobertura de prensa tecnológica, junio de 2026).
- **Adopción:** a abril de 2026, cerca de 18 millones de personas habían verificado su humanidad mediante un Orb en 160 países, con más de 30 millones de usuarios totales de la app World y más de 500 millones de transacciones soportadas (cifra de febrero de 2026); en octubre de 2024 el proyecto ya había superado los 10 millones de verificaciones humanas (Fuente: The Block, "Sam Altman's World project passes 10 million human verifications"; cobertura de anuncios oficiales de World, 2026). World abrió una tienda insignia en Oxford Street, Londres, en 2026 como parte de su expansión física del hardware Orb.

## Contexto geopolítico y regulatorio

El activo con mayor relevancia regulatoria de esta ficha no es su mercado (pequeño en capitalización) sino el modelo de negocio subyacente: recolección biométrica masiva (escaneo de iris) a cambio de tokens, lo que ha chocado repetidamente con marcos de protección de datos en distintas jurisdicciones:

- **Kenia:** el Ministerio del Interior suspendió las operaciones de Worldcoin en agosto de 2023 por preocupaciones de seguridad financiera y privacidad, tras el registro de cientos de miles de personas (Fuente: CoinDesk, "Worldcoin Suspended by Kenya on Financial Security and Privacy Concerns", 2023-08-02). En 2025, la Corte Superior de Kenia falló en contra del proyecto, ordenando la eliminación de los datos biométricos de usuarios locales (incluyendo imágenes faciales y escaneos de iris) dentro de siete días, y prohibiendo la recolección o el procesamiento de nuevos datos biométricos en el país (Fuente: The Block, "Kenya court rules against Sam Altman's World, orders data deletion and halts biometrics collection").
- **España:** la Agencia Española de Protección de Datos (AEPD) ordenó en marzo de 2024 el cese temporal (hasta tres meses, luego extendido hasta fin de 2024) de la recolección y el procesamiento de datos personales de Worldcoin, tras recibir denuncias sobre información insuficiente a los usuarios, recolección de datos de menores e imposibilidad de retirar el consentimiento (Fuente: The Block, "Spain bans Worldcoin for up to three months amid broader investigation", 2024). A comienzos de 2026, Tools for Humanity intentó reanudar operaciones en España con una nueva sede en Barcelona; la AEPD respondió el 13 de febrero de 2026 con una advertencia preventiva formal, señalando que el plan de escaneo de iris podría volver a incumplir el Reglamento General de Protección de Datos (RGPD/GDPR) — es decir, a la fecha de corte de este análisis, la situación en España sigue sin resolverse de forma definitiva.
- **Portugal:** el regulador de datos ordenó en marzo de 2024 el cese de la recolección de datos biométricos por 90 días, señalando un riesgo alto para los derechos de protección de datos de los ciudadanos; más de 300.000 personas habían entregado sus datos biométricos en el país (Fuente: The Block, "Worldcoin ordered to halt biometric data collection in Portugal").
- **Hong Kong:** la Oficina del Comisionado de Privacidad para Datos Personales (PCPD) ordenó en mayo de 2024 el cese de todas las operaciones de escaneo de iris, calificando la recolección de datos faciales e de iris de al menos 8.302 personas como "innecesaria y excesiva" (Fuente: CoinDesk, "Worldcoin Operations Violate Privacy and Should Cease, Hong Kong Regulator Says", 2024-05-22).
- **Corea del Sur:** la Comisión de Protección de Información Personal (PIPC) multó a Worldcoin y a Tools for Humanity con 1.100 millones de wones (~US$830.000) por no informar adecuadamente a los usuarios sobre el propósito y el período de conservación de los datos de iris recolectados, y por no ofrecer un formulario de consentimiento traducido al coreano antes de marzo de 2024 (Fuente: The Block, "South Korea fines Worldcoin and Tools For Humanity for data privacy violations").
- **Singapur:** las autoridades abrieron en septiembre de 2024 una investigación sobre siete personas por prestar servicios de Worldcoin sin la debida autorización (Fuente: CoinDesk, "Singapore Investigating Seven People for Providing Worldcoin Services", 2024-09-11).
- **Unión Europea (marco general MiCA / RGPD):** más allá de los casos puntuales de España y Portugal, el patrón regulatorio en la UE ilustra la tensión entre el marco MiCA (que regula principalmente la emisión y prestación de servicios sobre criptoactivos) y el RGPD (que regula la protección de datos biométricos, categoría de "dato sensible" bajo el artículo 9 del RGPD). El caso Worldcoin muestra que, para proyectos cripto con componente de identidad biométrica, el riesgo regulatorio relevante para el precio del token proviene tanto del RGPD como de la propia regulación de criptoactivos.
- **Estados Unidos (SEC / CFTC):** no se identificó, dentro de las fuentes de confianza consultadas, una acción de cumplimiento formal de la SEC o la CFTC específicamente contra Worldcoin/WLD a la fecha de corte; el principal frente regulatorio del proyecto ha sido de protección de datos, no de valores o derivados financieros. Se documenta como "dato no verificado" cualquier acción de la SEC/CFTC más allá de lo aquí señalado.
- **Efecto sobre el precio y la narrativa:** la sucesión de suspensiones (Kenia, España, Portugal, Hong Kong) entre 2023 y 2024 coincidió con el fin del rally inicial de WLD y contribuyó, junto con la presión de oferta por desbloqueo de tokens, al prolongado mercado bajista de 2024-2025. La reapertura intentada en España en 2026 y la reducción del ritmo de emisión desde el 24 de julio de 2026 son, en opinión del analista (ver sección de Escenarios), los principales catalizadores a vigilar en el corto plazo.
- **Correlación con política monetaria y apetito de riesgo global:** como la mayoría de los criptoactivos fuera de Bitcoin, WLD es un activo de "riesgo" (risk-on) cuyo comportamiento tiende a correlacionarse con las condiciones de liquidez global y la política monetaria de la Reserva Federal de EE. UU.: entornos de tasas más bajas o expectativas de recorte tienden a favorecer flujos hacia activos especulativos como WLD, mientras que entornos restrictivos o de aversión al riesgo golpean primero y con más fuerza a altcoins pequeñas como esta, dado su bajo tamaño relativo (fuera del top 10) y su elevada dependencia de flujos especulativos minoristas. Esta relación es una lectura del analista basada en el comportamiento histórico general del mercado cripto, no una cifra verificada específica para WLD.

## Escenarios

*Las proyecciones siguientes son opinión y ejercicio de escenarios del analista, no datos verificados ni asesoría financiera.*

- **Alcista:** El recorte del 43% en la emisión diaria de WLD (vigente desde el 24 de julio de 2026) reduce de forma sostenida la presión de venta estructural; en paralelo, la integración de World ID con plataformas de terceros (verificación anti-bot para redes sociales, aplicaciones de citas, herramientas de firma digital) impulsa la demanda de "prueba de humanidad" en un contexto de proliferación de contenido generado por IA, elevando el uso real de la red y, con ello, la narrativa de adopción del token. Bajo este escenario, WLD podría recuperar terreno de forma sostenida hacia la zona de US$1–2, revirtiendo buena parte de la caída de 2025, aunque sin garantía de volver a niveles del ATH de 2024.
- **Base:** WLD continúa cotizando como una altcoin de nicho, fuera del top 10 por capitalización, con alta volatilidad ligada a noticias puntuales (avances de World ID, resultados regulatorios en España, novedades sobre Tools for Humanity) más que a una tendencia definida. El precio se mantiene en un rango amplio, oscilando aproximadamente entre US$0,30 y US$0,80, sin una ruptura clara de tendencia en ningún sentido durante el resto de 2026.
- **Bajista:** Las dificultades financieras de Tools for Humanity (recortes de personal reportados en junio de 2026, dificultad para generar ingresos) se agravan, la expansión regulatoria en Europa (España) vuelve a bloquearse de forma definitiva, y la presión de oferta —pese al recorte de emisión— sigue superando a la demanda real por el token. En este escenario, WLD podría revisitar o incluso perforar el mínimo histórico de mayo de 2026 (~US$0,23), consolidándose como uno de los peores desempeños relativos entre los activos cripto de mediana/baja capitalización.

## Riesgos

*Riesgos identificados por el analista para fines educativos; no constituyen recomendación de inversión.*

1. **Riesgo regulatorio de datos biométricos:** el modelo de negocio central (recolección de iris) sigue bajo escrutinio activo en múltiples jurisdicciones (España en 2026, antecedentes en Kenia, Portugal, Hong Kong, Corea del Sur, Singapur); una prohibición generalizada en un mercado grande (p. ej. la UE en su conjunto) sería un catalizador bajista mayor.
2. **Riesgo de emisión/dilución:** aun con el recorte de julio de 2026, el suministro circulante de WLD sigue creciendo hacia el tope de 10.000 millones de tokens (actualmente ~3.500 millones en circulación), lo que implica dilución estructural para tenedores existentes durante años.
3. **Riesgo de concentración y gobierno corporativo:** la dependencia del proyecto de Tools for Humanity como empresa desarrolladora, de su salud financiera (reportes de recortes de personal en 2026) y de la figura de Sam Altman (cuya atención principal está en OpenAI) representa un riesgo de ejecución y de continuidad.
4. **Riesgo de baja capitalización y liquidez:** al estar fuera del top 10 (puesto ~48-55), WLD tiene menor liquidez y mayor sensibilidad a movimientos bruscos de precio frente a las 10 principales criptomonedas.
5. **Riesgo de correlación macro:** como activo de riesgo, WLD es vulnerable a episodios de aversión al riesgo global, endurecimiento de la política monetaria de la Reserva Federal o caídas generalizadas del mercado cripto lideradas por Bitcoin.
6. **Riesgo narrativo/tecnológico:** la tesis de inversión de WLD depende en gran medida de que la necesidad de "prueba de humanidad" frente a bots de IA se vuelva un caso de uso masivo; si esa narrativa no se materializa en adopción real y sostenida, el token podría perder relevancia frente a proyectos competidores de identidad digital (p. ej. Humanity Protocol).

## Fuentes consultadas

- CoinMarketCap — https://coinmarketcap.com (datos de precio, capitalización y ranking, consultado 2026-07-11 a 2026-07-17)
- CoinGecko — https://www.coingecko.com (datos de precio, capitalización y ranking, consultado 2026-07-15 a 2026-07-17)
- World Foundation / documentación oficial — https://world.org y https://foundation.world.org (tokenomics, gobernanza, anuncios de producto)
- World Whitepaper — https://whitepaper.world.org (tokenomics y calendario de emisión)
- The Block — "Kenya court rules against Sam Altman's World, orders data deletion and halts biometrics collection"; "South Korea fines Worldcoin and Tools For Humanity for data privacy violations"; "Spain bans Worldcoin for up to three months amid broader investigation"; "Worldcoin ordered to halt biometric data collection in Portugal"; "Hong Kong orders Worldcoin to cease local operations, calls iris data collection 'excessive'"; "Worldcoin's Spain ban extended to end of 2024"; "Sam Altman's World project passes 10 million human verifications"; "World raises $135 million via WLD token sale to expand across the US"; "Worldcoin, Sam Altman's Crypto Project, Is Building a Layer-2 Chain" — https://www.theblock.co
- CoinDesk — "Worldcoin Suspended by Kenya on Financial Security and Privacy Concerns" (2023-08-02); "Worldcoin Operations Violate Privacy and Should Cease, Hong Kong Regulator Says" (2024-05-22); "Singapore Investigating Seven People for Providing Worldcoin Services" (2024-09-11); "Sam Altman's Crypto Project Worldcoin Raises $115M, Led by Blockchain Capital" (2023-05-25); "World token jumps as Sam Altman reportedly eyes a biometric social network to kill off bots" (2026-01-28) — https://www.coindesk.com
- Decrypt — "Why Worldcoin Built an Ethereum Network Specifically for Humans"; "Worldcoin Reveals Ethereum Chain Where 'Verified' Humans Get Priority" — https://decrypt.co
- Bloomberg — "Eyeball-Scanning Worldcoin Project Looks to OpenAI Partnership" (2024-04-25); perfil corporativo de Tools for Humanity Corp — https://www.bloomberg.com
