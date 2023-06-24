# Proyecto_discretas
Solución al problema 5 solicitado en el proyecto de la materia de Matemáticas discretas.
# Descripción del problema
Las ciudades en un mapa están conectadas por varias carreteras. El número de carreteras entre cada ciudad está en un arreglo y la ciudad es 0 la ubicación inicial. El número de carreteras de ciudad 0 a ciudad es 1 el primer valor del arreglo, de ciudad 1 a ciudad 2 es el segundo, y así sucesivamente.

¿Cuántos caminos hay desde la ciudad 0 hasta la última ciudad de la lista, módulo 1234567?

# Ejemplo
n = 4

rutas = [3,4,5]

Hay 3 caminos a la ciudad 1, 4 caminos a la ciudad 2 y 5 caminos a la ciudad 3. El número total de caminos es 3x4x5 mod 1234567 = 60.

int n: el número de ciudades
int rutas[n-1]: el número de rutas entre ciudades

# Lo que se le ingresa
La primera línea contiene un número entero T de test que elaborara, siguen los casos de prueba.

Cada caso de prueba tiene 2 líneas en el txt.
La primera línea contiene un número entero N(el número de ciudades).
La segunda línea contiene N - 1 números enteros separados por espacios donde el i-ésimo número denota el número de rutas, Ni, desde la ciudad Ti hasta Ti+1

# Lo que regresa

int: el número total de rutas, módulo 1234567.

# Limites de entrada

1 <= T <= 1000

2 < N <= 100

1 <= rutas[i] <= 1000

# Instrucciones de uso

Se descargara el archivo "town.c" (código fuente) y el archivo "input5.txt" (entradas de muestra para el problema) y se colocarán en una misma carpeta.
El archivo "town.c" se recomienda compilar en el programa Dev-C++, al compilar la consola directamente acabara el programa, pero habrá creado un nuevo archivo "output5.txt" que contendra el resultado del problema.


# Entrada de muestra
2

3

1 3

4

2 2 2

# Salida de muestra

3

8
