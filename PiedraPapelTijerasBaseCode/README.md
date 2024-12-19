# Implementación del Juego "Piedra, Papel o Tijera"

Este es el código fuente del clásico juego "Piedra, Papel o Tijera". El jugador compite contra la computadora eligiendo una de las tres opciones (piedra, papel o tijera), mientras que la computadora selecciona una opción de manera aleatoria.

## Archivos

- **juego_piedra_papel_tijera.c**: Código fuente del juego en C.
- **juego_piedra_papel_tijera.cpp**: Código fuente del juego en C++.

## Descripción

El juego es simple:
- El jugador selecciona una opción (Piedra, Papel o Tijera).
- La computadora selecciona una opción aleatoria.
- El programa compara ambas elecciones y determina el resultado: ganar, perder o empate.

### Funcionalidades:

- **Generación de elección aleatoria** para la computadora utilizando la función `rand()`.
- Comparación de la elección del jugador y la computadora para determinar el resultado.
- Mostrar el resultado del juego: **Ganar, Perder o Empatar**.

### Ejecución

#### Compilar y ejecutar el código en C:

1. Para compilar el archivo en C, usa el siguiente comando en la terminal:
   ```bash
   gcc juego_piedra_papel_tijera.c -o piedra_papel_tijera