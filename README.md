# Particle Swarm Optimization en Julia y C 馃捇

**Integrantes del equipo:**

* Malv谩ez Flores Axel Daniel
* Peralta Rionda Gabriel Zadquiel


## Objetivo del Proyecto
El objetivo del proyecto es presentar los conceptos b谩sicos del algortimo de optimizaci贸n por enjambre de part铆culas ("Particle Swarm Optimization",PSO) al igual que hacer una implementaci贸n de este algoritmo en el lenguaje de programaci贸n Julia y C haciendo uso de memoria distribuida.

## Carpetas
### docs
Carpeta que contiene el archivo en pdf que explica detalladamente cada parte del proyecto desde una introducci贸n al algoritmo hasta las implementaciones en Julia y C.

### main

Contiene dos **subcarpetas** en las que se encuentran los archivos ya sea para el lenguaje de programaci贸n:

* C
* Julia

se implement贸 el algoritmo secuencial de una dimensi贸n para Julia, el algoritmo en paralelo utilizando la librer铆a MPI para Julia y C y en paralelo para varias dimensiones en Julia.

### results

Contiene dos **subcarpetas** en las que se encuentran los archivos ya sea para el lenguaje de programaci贸n:

* C
* Julia

y los cuales son archivos en formato .txt que contienen una serie de ejecuciones de los algoritmos con su respectivo tiempo (que tarda en correr el programa).


##聽PSO
### Algoritmo PSO
1. Inicializar la poblaci贸n de las part铆culas
2. Evaluar la poblaci贸n en la funci贸n objetivo y elegir la mejor part铆cula 
3. while (criterio de paro)
4. for (todas las particulas en todas las dimensiones)
5. Generar una nueva velocidad
6. Calcular una nueva posici贸n
7. Evaluar la funci贸n objetivo y elegir la mejor part铆cula
8. end for
9. Actualizar la mejor part铆cula de la poblaci贸n
10. end while


