<p align="center">
  <img src="assets/banner.png" alt="Hielo a la izquierda, calor a la derecha y el cristal de Kvothesson colgado de la línea de alta tensión" width="100%">
</p>

<p align="center">
  <a href="https://kvothesson.com">kvothesson.com</a> ·
  <a href="https://www.youtube.com/@Kvothesson">YouTube</a> ·
  <a href="https://github.com/kvothesson/ar-plugins">ar-plugins</a>
</p>

<p align="center"><sub><i>Workshop of an Argentine maker: apps, games, generative music and code-only video.
Most things are in Spanish; <a href="https://github.com/kvothesson/chasqui">Chasqui</a> and
<a href="https://github.com/kvothesson/procedural-anime">procedural-anime</a> are documented in English.</i></sub></p>

Esto es el taller. Acá se arma, se prueba y se archiva todo: apps, herramientas para Argentina,
juegos, música generativa, los videos del canal y un universo cyberpunk criollo (Austral) que le
da sentido a los nombres raros. Casi todo corre sobre Claude Code.

## Lo que está andando

| | |
|---|---|
| **[Tachán](https://kvothesson.com/tachan/)** | Compartís en el celu y aparece en la compu. Sin servidores. |
| **[ar-plugins](https://github.com/kvothesson/ar-plugins)** | 15 plugins de Claude Code y Codex sobre Argentina: dólar e inflación en vivo, trámites, sueldos, derechos, salud y monotributo. Datos de fuentes oficiales, nada de blogs. |
| **[Chasqui](https://kvothesson.com/chasqui/)** | Traductor de voz en tiempo real para Windows: llamadas en cualquier app y videos en vivo. |
| **[Los Decretos](https://kvothesson.com/decretos/)** | Todos los presidentes argentinos en una sola voz, proponiendo políticas públicas reales. |
| **[Radio Austral](https://kvothesson.com/radio/)** | Música generativa infinita, hecha con Strudel en el navegador. |
| **[verbo](https://github.com/kvothesson/verbo)** | Coding agent en tu terminal a costo cero, en un solo archivo de Python. |

```
/plugin marketplace add kvothesson/ar-plugins
```

## Juegos, música y video

**[procedural-anime](https://github.com/kvothesson/procedural-anime)** · Shorts verticales estilo anime
hechos solo con código: Blender, Python y sonido sintetizado.

**[Ruta 404](https://kvothesson.com/ruta-404/)** · Exploración en canvas 2D del universo Austral.

**[Babel](https://kvothesson.com/babel/)** · La Biblioteca de Babel, navegable en 3D.

**[aparecidos](https://github.com/kvothesson/aparecidos)**, **[daemons](https://github.com/kvothesson/daemons-plugin)** y
**[pombero](https://github.com/kvothesson/pombero-exe)** · El bestiario del folklore metido en la compu.

## El archivo, que también sirve

Acá hay repos viejos que no borro, porque son el registro de cómo se llegó a lo de arriba.
Casi todos son cuatro ideas intentadas muchas veces:

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
