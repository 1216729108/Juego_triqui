# Triqui (Tres en línea) - Pygame

Este proyecto es un sencillo juego de Triqui (también conocido como Tres en línea o Tic-Tac-Toe) implementado en Python usando la librería [Pygame](https://www.pygame.org/).

## ¿Cómo jugar?

- El juego es para dos jugadores: "X" y "O".
- Haz clic en una celda vacía para colocar tu ficha.
- El primer jugador en alinear tres de sus fichas (horizontal, vertical o diagonal) gana.
- El juego termina cuando hay un ganador o el tablero está lleno.

## Estructura del código

- [`Codigo.py`](triqui/Codigo.py): Archivo principal que contiene toda la lógica del juego.
- Carpeta `herramientas/`: Contiene las imágenes usadas para el fondo y las fichas.

## Requisitos

- Python 3.8 o superior
- Pygame

## Instalación

1. Instala las dependencias:
    ```sh
    pip install pygame
    ```
2. Asegúrate de que las imágenes `fondo.png`, `circle.png` y `x.png` estén en la carpeta `herramientas/`.

## Ejecución

Desde la carpeta `triqui/`, ejecuta:

```sh
python Codigo.py
```

## Créditos

- Imágenes: Incluidas en la carpeta `herramientas/`.
- Código: Desarrollado para fines educativos.

---

¡Disfruta jugando Triqui!