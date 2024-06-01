# Descripción del Juego


## Variables Principales

* goLeft: Indica si el jugador se mueve a la izquierda.
* goRight: Indica si el jugador se mueve a la derecha.
* isNicetry: Indica si el juego ha terminado (ganado o perdido).
* score: Guarda la puntuación del jugador.
* ballx: Controla la dirección y velocidad horizontal de la bola.
* bally: Controla la dirección y velocidad vertical de la bola.
* playerSpeed: La velocidad del jugador.
* rnd: Generador de números aleatorios para colores y velocidad de la bola.
* blockArray: Arreglo de bloques en el juego.


## Métodos Principales

* Nicetry: Detiene el juego y muestra un mensaje de victoria o derrota.
* EnemiesPlace: Crea y coloca 15 bloques en el juego y llama a setupGame para inicializar.
* Quitarbloques: Elimina todos los bloques del juego.
* Erzebet: Controla el temporizador del juego:
	- Mueve al jugador y la bola.
	- Verifica colisiones con los bordes, el jugador y los bloques.
	- Actualiza la puntuación y verifica si el jugador gana o pierde.
* Abajo: Maneja el movimiento del jugador al presionar teclas.
* Press: Detiene el movimiento del jugador al soltar las teclas y reinicia el juego con Enter si ha terminado.