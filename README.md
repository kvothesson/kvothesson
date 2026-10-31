# kvothesson

Construyo herramientas para el ecosistema argentino y un universo cyberpunk criollo.
Casi todo corre sobre Claude Code.

## Lo que está vivo

**[ar-plugins](https://github.com/kvothesson/ar-plugins)** · Marketplace de plugins de Claude Code para Argentina.
15 plugins que traen datos reales de fuentes primarias: dólar e inflación ([arca](https://github.com/kvothesson/arca)),
trámites de ANSES y ARCA ([tramite](https://github.com/kvothesson/tramite)), paritarias y sueldos ([laburo](https://github.com/kvothesson/laburo)),
marco legal ([derecho](https://github.com/kvothesson/derecho)), facturación de monotributo ([facturar](https://github.com/kvothesson/facturar)),
y más. Nada de scraping de blogs: INDEC, IGN, organismos oficiales.

```
/plugin marketplace add kvothesson/ar-plugins
```

**[verbo](https://github.com/kvothesson/verbo)** · Coding agent en tu terminal a costo cero.
Un solo archivo de Python, corriendo sobre tiers gratis (Groq, Gemini, OpenRouter) o Ollama local.

**[pombero](https://github.com/kvothesson/pombero-exe)** · Un asistente que vigila tu hardware desde las sombras.
Guardián del sistema con personalidad folklórica.

**[daemons](https://github.com/kvothesson/daemons-plugin)** y **[mechas](https://github.com/kvothesson/mechas-plugin)** ·
Agentes del bestiario guaraní y mechas neuronales. Cyber folklore argentino como skills de sistema.

## El cementerio, que también sirve

Este perfil tiene repos viejos que no borro, porque son el registro de cómo se llegó a lo de arriba.
Casi todo lo que hay acá son cuatro ideas intentadas muchas veces:

**"Un LLM que lee tu repo y hace algo con eso"** se intentó siete veces entre 2024 y 2025:
`adhmcr`, `repo-scribe`, `repo-whisper`, `file-whisperer`, y tres más que quedaron privadas.
Todas funcionaban. Ninguna se usaba. El problema nunca fue el modelo, era el formato:
una CLI más que instalar y recordar. La idea recién sirvió cuando dejó de ser un programa
y pasó a ser un plugin que vive adentro de la herramienta que ya estabas usando.
De ahí salieron `ar-plugins` y `verbo`.

**"Lenguaje natural a script ejecutable"** fueron `capibara` y `capibara-core`. Mismo destino,
misma conclusión.

**"Arenas donde pelean IAs"** fue `cyber-ragnarok` y un par de intentos privados. Nunca llegó
a producto, pero el motor de simulación quedó y hoy corre experimentos de emergencia de lenguaje.

**"Dato duro argentino más visualización"** fue `argentina-oil-boom` y una calculadora de créditos UVA.
Esa sí escaló, y es la mitad de lo que hace `ar-plugins` hoy.

Siete intentos de lo mismo antes de encontrar el envase correcto. Lo dejo escrito porque el
recorrido es más útil que el resultado.

## Afuera de GitHub

Canal de YouTube donde cruzo folklore argentino con IA generativa, y un universo narrativo
(Austral) que le da sentido a los nombres raros de la mitad de estos repos.
