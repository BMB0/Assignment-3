Juego

Descripcion:

El juego consiste en 25 espacios conectados con lineas verticales, horizontales y diagonales

El juego puede dividirse en dos fases.

Primera Fase:

Se tienen 4 fichas negras y 4 piezas rojas. Los jugadores deberan seleccionar entre las las casillas disponibles y realizar un moviento, para el final de esta fase hay 8 fichas en el tablero, 4 negras y 4 rojas

Es posible ganar en la primera fase, si nadie gana, se pasa a la segunda fase

Segunda Fase:
En esta fase los jugadores seleccionan una de sus fichas en el tablero y en cada turno se puede mover las fichas en un campo adyacente vacio, ya sea vertical, horizontal o diagonal.

Esta fase continua hasta que uno de los jugadores sea el ganador.

Reglas
- Si un jugador forma una linea de 4 fichas Gana la partida (Horizontal, Diagonal y Vertical)

- Si un jugador forma un cuadrado Gana la partida

- Una vez asignadas las 4 piezas el jugador puede seleccionar una y moverla a una casilla sin asignacion


DESCRIPCIÓN DE LA SOLUCIÓN:
Para la implementación de adversarial search, se usó tres algoritmos: min max, alpha beta pruning y min max with depth (Con y sin la variante alpha beta pruning). Los algoritmos mencionados con anterioridad fueron probados para ver su desempeño jugando contra humanos en el Juego Teeko. Así también se usó una huerística que tiene una matriz que representa cada casilla con una ponderación establecida donde el objetivo de la misma es posicionar las fichas en posiciones donde existan más posibilidades de ganar.

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/winning_moves_position.png?raw=true)

Posteriormente, se toma en cuenta los turnos, mientras que en menos turnos se llegue a realizar la jugada vale más y si es que encuentra una solución ganadora esta vale más aun(Strength).

EXPERIMENTOS:

- Tiempos de Ejecucion por Turno

- Test 1 Con ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_1.png?raw=true)

- Test 1 Sin ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_1.png?raw=true)

- Test 1 Con Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_1.png?raw=true)

- Test 1 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test1.png?raw=true)

- Test 2 Con ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_2.png?raw=true)

- Test 2 Sin ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_2.png?raw=true)

- Test 2 Con Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_2.png?raw=true)

- Test 2 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test2.png?raw=true)

- Test 3 Con ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_3.png?raw=true)

- Test 3 Sin ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_3.png?raw=true)

- Test 3 Con Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_3.png?raw=true)

- Test 3 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test3.png?raw=true)

- Estados Expandidos Test 1

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Expanded_States_test1.png?raw=true)

- Estados Expandidos Test 2

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Expanded_States_test2.png?raw=true)


- Grafica de Barras

- Comparaciones de Tiempo en la ejecucion de los algoritmos 




• Experimentos realizados.
• Conclusiones.
Ademas, se tendra una seccion donde se indicara como ejecutar el proyecto (Installation Guide).
