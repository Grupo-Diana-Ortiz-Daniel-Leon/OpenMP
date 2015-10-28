# Tarea de OpenMP  - Programación en paralelo


## Contenido de este repositorio

Este repositorio contiene los archivos que corresponden a la implementación de los ejercicios propuestos, asi como los ejemplos sobre OpenMP que se presentaron durante la clase, compilados y ejecutados.

* `Makefile` en este archivo contiene la mayoria de los códigos del repositorio con las directrices de compilación de cada uno. Quedo en construcción.

* `helloword-2.c` En este programa se realizó el ejercicio para verificar los cambios en las iteraciones propuestas.

* `parallel_00.c` En este código se puede ver en acción la invocación en paralelo de un bloque de código en C y como se especifica que una variable sea tomada como una variable privada y accesible solo para un hilo.

* `parallel_01.c` En este programa se muestra como se puede indicar un número diferentes de hilos para llevar a cabo una tarea. 

* `parallel_02.c` En este programa se muestra como se puede paralelizar un ciclo `for`. 

* `parallelblock_00.c` En este programa se muestra como se pueden paralelizar diferentes bloques de código a través de las directivas `sections` y `section`. 
* `parallelfor_00.c` En este programa se muestra la paralelización de un ciclo `for` pero además muestra una directiva de compilación llamada `reduction` que permite consolidar el valor parcial de diferentes hilos en una sola variable.

## Ejercicios propuestos

* `pi-3.c` implementación con la paralelización del cálculo pi.
* `montecarlopi1.c` implementación con la paralelización del cálculo montecarlopi.


