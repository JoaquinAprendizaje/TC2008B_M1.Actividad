### Análisis del impacto de agentes al tiempo de limpieza.
A través de la ejecución del programa y los valores recibidos del mismo, se ha identificado que la simulación realizada, debido a la aleatoridad que presenta, no suele tener una gran diferencia de impacto en cuestiones de tiempo al tener una mayor cantidad de agentes.
Se concluye esto al realizar pruebas en un tablero de 10x10 tanto con 5 agentes, como con 10 y 20, donde los resultados fueron los siguientes:


| Agentes | Tiempo1 | Tiempo2 | Tiempo3 |
| 5 | 0:00:00.054036 | 0:00:00.103895	 | 0:00:00.067978 |
| 10 | 0:00:00.039537 | 0:00:00.055086	 | 0:00:00.045290 |
| 20 | 0:00:00.085303 | 0:00:00.052178	 | 0:00:00.042850 |

Dicho esto, es importante mencionar que, a pesar de que el timepo parece no verse afectado por la cantidad de agentes, la cantidad de *steps* a realizar disminuye considerablemente mientras más agentes haya.

Al realizar pruebas como la anteriormente mencionado, podemos ver que la cantidad de *steps* realizada por las pruebas de 5 agentes, oscila entre 170 y 200. Mientras que con 20 agentes no excede de 100.
