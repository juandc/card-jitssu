# card-jitssu

🐧🃏 Juego de cartas usando Flask, Socket.IO, PostgreSQL y (frontend por definir).

## TODOs y requerimientos

- Elegir un hosting para Postgres (seguramente Heroku o ElephantSQL)
- Definir las tablas y relaciones

- Escribir el código backend en Flask: https://flask-socketio.readthedocs.io/en/latest/
-- Guardar los datos en la base de datos
-- Trasmitir la información del juego con el frontend usando socket.io


- Escribir el código frontend
-- UI (basando el estilo un poco en algún template de Figma: https://www.figma.com/community/file/847908728053432821, https://github.com/synapse709/Blueframe)
-- Dashboard con el perfil de cada usuario.
-- Métricas/gráficas de partidas ganadas, perdidas y abandonadas, filtrando por 
-- Posibilidad de definir antes de combate qué estrategia utilizará para medir después los ressultados

Lógica del juego:
- Cartas de Fuego, Agua y Nieve (pro + tierra y aire)
- Cada carta tiene un nivel del 1 al 10 (pro + 11-15)
- Cada carta puede tener encantamiento (además de su función normal, habilita o deshabilita otra función en el juego)


Pendiente:

- ¿Tabla de juegos/partidas con columna de estado (pendiente?, abandonado antes de empezar, abandonado en partida, completado)?
- ¿Cómo se conecta un jugador a una partida? No como la crea, sino cómo se une... Pss, hay "Rooms"
- ¿Es necesario, además de las partidas, hacer una tabla de colchonetas (lugare donde sse puede hacer la partida)/
- ¿Generar un código con el que puedas unirte a una partida?
- ¿Nivel de cada usuario (cinturon de pingüino) por cantidad de partidas ganadas? ¿Por puntos acumulados? ¿¡PUNTOS!?
- ¿Compramos niveles 10+ y encantamientos con puntos...?
- ¿Conseguir puntos para cambiar por "dinero"...? ¿Es necesario?
- Pierdes puntos o dinero por abandonar la partida, ganas por perder y ganas más por ganar.
