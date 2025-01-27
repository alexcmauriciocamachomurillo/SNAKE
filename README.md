# SNAKE
[![1366-2000.jpg](https://i.postimg.cc/vH9kfjd2/1366-2000.jpg)](https://postimg.cc/VdfKcKvX)
<p align="center" > 
  
# DESCRIPCION

El programa de SNAKE es una implementacion basica del popular juego "SNAKE GAME" utilizando la biblioteca pygame en Python. A continuación, te explico los elementos principales del programa y cómo funciona:
![image](https://github.com/user-attachments/assets/3bdbab0e-0989-4cb4-aabb-3450b0279931)

# Elementos Del Programa
Lo primero y lo mas importante ya que sin este paso no se podria hacer el programa ,  Importar las bibliotecas necesarias:
```
 import pygame
 import time
 import random
```
### luego definir color y dimenciones :
```
white = (255, 255, 255)
black = (0, 0, 0)
red = (213, 50, 80)
green = (0, 255, 0)
blue = (50, 153, 213)

width = 800
height = 600
```
### Bucle principar del juego
```
def gameLoop():
    game_over = False
    game_close = False

    x1 = width / 2
    y1 = height / 2

    x1_change = 0
    y1_change = 0

    snake_list = []
    length_of_snake = 1

    foodx = round(random.randrange(0, width - snake_block) / 10.0) * 10.0
    foody = round(random.randrange(0, height - snake_block) / 10.0) * 10.0



