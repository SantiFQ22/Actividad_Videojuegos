# Pac-Man en Python (versión personalizada)

Este proyecto es una versión modificada del clásico juego **Pac-Man**, desarrollada en **Python** usando la librería `turtle` y el módulo `freegames`.


# Cambios

#### Personalización de colores

-   **Pac-Man** ahora es de color **verde** en lugar del clásico amarillo.
    
-   **Fantasmas** ahora son de color **rosa** en lugar de rojo.
    

Estos cambios se realizaron en la función `move()` modificando las líneas:

`t.dot(20, 'yellow') → t.dot(20, 'green')
t.dot(20, 'red') → t.dot(20, 'pink')`
