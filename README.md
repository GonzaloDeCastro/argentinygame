# Batallas Argentinas

Juego de estrategia por turnos, al estilo Fire Emblem, sobre batallas de la historia argentina.
Se juega en el navegador: no hace falta instalar nada. El juego es el archivo `index.html`.

## Batallas

| # | Batalla | Fecha | Lugar |
|---|---|---|---|
| 1 | Tucumán | 24 de septiembre de 1812 | Campo de las Carreras, Tucumán (Argentina) |
| 2 | San Lorenzo | 3 de febrero de 1813 | Convento de San Carlos, San Lorenzo, Santa Fe (Argentina) |
| 3 | Chacabuco | 12 de febrero de 1817 | Cuesta de Chacabuco, al norte de Santiago (Chile) |
| 4 | Maipú | 5 de abril de 1818 | Llanos de Maipú, cerca de Santiago (Chile) |

## Cómo jugar

Abrí `index.html` en el navegador (o la página de GitHub Pages del repositorio).
La pantalla de inicio muestra una **cronología** con las batallas y los hitos que las unen, y un **mapa** con el lugar y el país de cada una.

- **Campaña cronológica:** cada batalla se desbloquea al ganar la anterior.
- **Batalla libre:** elegís cualquier batalla.
- **Guardar / cargar partida:** botón del panel lateral (en tu turno). Hay 3 ranuras y un autoguardado al inicio de cada turno. Las partidas quedan en el navegador del dispositivo.

El juego trae un instructivo (botón o tecla **H**) con los pasos, el triángulo de armas y consejos de estrategia.

- Clic en una unidad azul y pasá el mouse por las casillas azules: una flecha muestra el camino. Con un clic la unidad camina hasta ahí; después elegí **Atacar** o **Esperar**.
- Pasá el mouse sobre un enemigo para ver el pronóstico del combate.
- **T** muestra la amenaza enemiga. **Esc** o clic derecho vuelven un paso atrás.
- Hay tres dificultades: Fácil, Normal y Difícil.

## Notas

- Los diálogos son una dramatización: no son citas textuales de los personajes históricos. Las cifras y los nombres del final de San Lorenzo salen del parte de San Martín del 3 de febrero de 1813.
- Todo el arte se genera por código (canvas); los efectos de sonido, con Web Audio.
- El sonido es opcional y está apagado por defecto. En San Lorenzo suena la Marcha de San Lorenzo si existe el archivo `assets/marcha-san-lorenzo.mp3` (no se incluye en el repositorio); si no está, suena música sintetizada, igual que en las otras batallas.
