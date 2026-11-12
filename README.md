# skylaunch-eventos

Fechas y ajustes de los eventos de Skylaunch. El juego lee `eventos.json` al abrirse
(https://jimmynelmos.github.io/skylaunch-eventos/eventos.json); sin red, usa los valores que lleva dentro.

Por evento (clave = id del evento en el juego): `inicio` y `fin` (`AAAA-MM-DD`, incluidos), `prob` (regalo por tramo, 0–1)
y `dorado` (parte de regalos dorados, 0–1). Cualquier otro valor se ignora.
