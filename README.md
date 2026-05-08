Changelog:
    Se han realizado actualizaciones en la lógica del juego para aumentar el rango de figuras que se pueden dibujar y en la parte visual para aumentar la cantidad de colores disponibles para utilizar. A continuación, se detallan los cambios principales respecto a la versión original:

Modificaciones en la parte visual

- Color naranja: Se agregó la opción de utilizar el color naranja. Se puede acceder a él presionando la tecla 'O'.

Nuevas funcionalidades en la lógica

- Círculo: Se desarrolló la función `circle()`, la cual dibuja un círculo desde el comienzo hasta el final propuesto por el usuario, tomando el valor absoluto del radio de la diferencia entre las coordenadas de x de inicio y final. Luego, dentro de un ciclo `for` el cual se ejecuta 360 veces, se aplica hacia adelante la fórmula de la circunferencia del círculo dividida entre 360 y se gira un grado en cada iteración del ciclo para formar el círculo. Al finalizar, la figura se rellena del color asignado por el usuario previamente.

- Rectángulo: Se desarrolló la función `rectangle()`, la cual dibuja un rectángulo desde el punto de inicio hasta el punto final indicado por el usuario. Calcula el ancho como la diferencia entre las coordenadas x de inicio y final, y la altura como la diferencia entre las coordenadas y. Luego recorre dos veces el par de lados opuestos (avanzando el ancho, girando 90°, avanzando la altura, girando 90°) para formar la figura. Al finalizar, el rectángulo se rellena del color asignado por el usuario previamente. Se puede acceder a esta figura presionando la tecla 'r'.

- Triángulo: Se desarrolló la función `triangle()`, la cual dibuja un triángulo isósceles a partir de dos clics del usuario. El primer clic define la esquina base izquierda y el segundo la esquina base derecha. El vértice superior se calcula como el punto medio en X entre ambos puntos, con una altura igual al ancho de la base para mantener proporciones simétricas. Los tres vértices se recorren con `goto` en orden: base izquierda → base derecha → vértice superior → cierre. Al finalizar, la figura se rellena del color asignado por el usuario previamente. Se puede acceder a esta figura presionando la tecla 't'.