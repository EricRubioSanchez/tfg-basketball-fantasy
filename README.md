# TFG Basketball Fantasy

Trabajo de Fin de Grado — Grado en Diseño y Desarrollo de Videojuegos.

Juego de baloncesto *fantasy* para un solo jugador, desarrollado en **Unity**, en el que el usuario crea su propia Liga fantasy, dirige un Equipo fantasy y compite contra mánagers controlados por la IA. Todos los Jugadores son artificiales: el usuario puede crearlos (posiciones, estadísticas y cara) y los Partidos se simulan y se pueden ver en 3D.

## Qué lo diferencia

- **Creación de Jugadores**: el usuario diseña sus propios Jugadores, con una o varias posiciones, sus estadísticas (incluidas altura y peso) y su cara.
- **Partidos simulados**: los Equipos fantasy se enfrentan entre sí en Partidos generados por un motor de simulación, en lugar de puntuar según una liga real.
- **Visor 3D**: cualquier Partido se puede ver reproducido en un pabellón 3D, con los mánagers en la banda como entrenadores.
- **Cartas coleccionables**: los Jugadores llegan en forma de Cartas con distintas Rarezas, que se consiguen en Cajas al terminar cada Jornada.

## Cómo se juega

1. **Crear la Liga fantasy**: el usuario elige entre muchas opciones de personalización (ver más abajo) o parte de un preset.
2. **Draft**: cada mánager elige por turnos, en serpiente, Cartas Básicas del Catálogo hasta completar su Plantilla inicial.
3. **Gestión entre Jornadas**: se alinea el Quinteto inicial, se asignan Roles y Estrategia de equipo, se reparten Habilidades, se hacen Intercambios y se descartan Cartas sobrantes.
4. **Jugar la Jornada**: el usuario decide cuándo se juega. Se simulan todos los Partidos al instante y se calculan los Puntos fantasy.
5. **Recompensas**: cada mánager recibe una Caja de jugadores y una Caja de habilidades.
6. Se repite hasta el final de la temporada (y la Fase final, si está activada), cuando se proclama al campeón.

La **Clasificación** suma los Puntos fantasy de cada Equipo fantasy más un Bonus de victoria por cada Partido ganado.

## Cartas, Rareza y coste

Un mismo Jugador puede aparecer en varias Cartas con distinta Rareza. La Rareza no cambia cómo juega el Jugador: determina cuántas Habilidades puede llevar la Carta y cuánto cuesta alinearla.

| Rareza     | Huecos de Habilidad | Coste |
| ---------- | ------------------- | ----- |
| Básica     | 0                   | 0     |
| Rara       | 1                   | 1     |
| Épica      | 2                   | 2     |
| Legendaria | 3                   | 3     |

- **Habilidades**: potenciadores de Puntos fantasy que se activan al completar un logro, una vez por Partido o de forma repetida. También tienen Rareza y se pueden reasignar entre Jornadas.
- **Coste de carta**: Rareza de la Carta + Rareza de cada Habilidad asignada.
- **Coste máximo de quinteto**: el Quinteto inicial no puede superarlo; aumenta con cada Jornada.
- **Plantilla**: tiene un tamaño máximo de Cartas. Puede superarse al abrir Cajas, pero hay que descartar antes de la siguiente Jornada.

## Equipo fantasy

- **Quinteto inicial**: cinco huecos por posición (Base, Escolta, Alero, Ala-pívot, Pívot). Solo estas Cartas juegan el Partido y puntúan.
- **Roles**: cada hueco recibe una forma de jugar (Ball handler, Primera espada, 3&D, Protector del aro…).
- **Estrategia de equipo**: ritmo, enfoque ofensivo, tipo de defensa y rebote ofensivo.
- **Intercambios**: de Cartas y Habilidades con los mánagers IA, que también proponen ofertas.
- **Identidad**: nombre, colores de equipación, escudo y aspecto del mánager.

## Personalización de la Liga fantasy

- Número de Equipos fantasy y dificultad de la IA.
- Vueltas de la temporada y Fase final opcional.
- Catálogo: qué Jugadores creados entran y cuántos se generan automáticamente.
- Rondas de Draft y tamaño máximo de Plantilla.
- Coste máximo de quinteto inicial y su incremento por Jornada.
- Sistema de puntuación: se parte de una plantilla predefinida y se ajustan los pesos. También se configura el Bonus de victoria.
- Contenido y probabilidades de las Cajas.
- Posiciones estrictas o jugar fuera de posición con penalización.
- Semilla para reproducir una Liga fantasy.

## Fuera de alcance

Quedan como trabajo futuro: modo online o multijugador, moneda y mercado, lesiones, cansancio y rotaciones, temporadas encadenadas, editor de Habilidades y versión móvil.
