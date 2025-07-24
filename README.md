# chopsticks_bot_algorithm
Algoritmo para elegir la jugada óptima en Chopsticks.

# Descripción 
Este algoritmo implementa Minimax de forma recursiva, evaluando un árbol de decisiones cuyo tamaño varía según las jugadas disponibles en cada turno.

Dado que Chopsticks es un juego relativamente simple, el bot alcanza un nivel de juego casi perfecto.

Sin embargo, como el juego puede entrar en bucles (repetición de estados), el árbol podría volverse infinito. Para evitarlo, se impone una profundidad máxima al árbol. Cuando se alcanza ese límite, se asigna un valor al estado final mediante una función heurística que evalúa la posición del jugador y del oponente.
