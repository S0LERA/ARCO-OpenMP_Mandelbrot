# ARCO-OpenMP_Mandelbrot
Repositorio para el trabajo de OpenMP de Arquitectura de Computadores, basado en paralelizar un programa secuencial para calcular fractales del conjunto Mandelbrot.

## Versiones
### Versión 0.1
 - Subida de los archivos del programa secuencial.
 - Subida de enunciado.

### Versión 0.5
 - Estructura paralela.
 - Separacion de B4 y B5.
 - No funcional.

### Versión 1.0
 - Primera version paralela funcional.
 - Cada hilo calcula valores para una region y todos guardan en una variable compartida.
 - Variables renombradas.

### Versión 2.0
 - Versión con schedule funcional.
   - Array de resultados bidimensional.
   - Añadido for paralelo para la planificación.
 - El número de hilos ahora se asigna automáticamente según los procesadores disponibles de cada equipo.

### Versión 2.5
 - Arreglado el fallo del número de hilos.
   - La variable numero de hilos no concordaba con la función de obtener los procesadores.