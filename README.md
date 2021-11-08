Se tiene un procesador multitarea que recibe y atiende los procesos de acuerdo al orden de llegada (no hay prioridad).
Cada nuevo proceso se guarda en una estructura tipo FIFO, y ahí permanece hasta que se llega su momento de ser atendido.
El Procesador permanece atendiendo cada procesos hasta terminarlo y en seguida toma el siguiente de la cola de espera.
Simular 300 ciclos con las siguientes condiciones.
En cada ciclo, existe un 39% de probabilidad de que llegue un nuevo proceso.
Cada proceso nuevo requiere entre 4 y 14 ciclos para ser atendido (totalmente aleatorio)
***Cada ciclo ira decrementando uno de los ciclos requeridos de cada tarea que llego
La información que se requiere conocer al finalizar (ir mostrando en la consola lo que esta ocurriendo):::
* Cuantos ciclos, estuvo vacía la cola (el procesador no tenia procesos por atender)
* Cuantos procesos si se atendieron completamente
* Al final de los ciclos cuantos procesos quedaron pendientes y cuanto sumaban sus ciclos pendientes
