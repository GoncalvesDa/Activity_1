Changelog
Se han realizado actualizaciones en la lógica del juego para aumentar el rango de figuras que se pueden dibujar y en la parte visual para aumentar la cantidad de colores disponibles para utilizar. A continuación, se detallan los cambios principales respecto a la versión original:

Modificaciones en la parte visual
- Color naranja: Se agregó la opción de utilizar el color naranja. Se puede acceder a él presionando la tecla 'O'.

Nuevas funcionalidades en la lógica
- Círculo: Se desarrolló la función circle(), la cual dibuja un círculo desde el comienzo hasta el final propuesto por el usuario, tomando el valor absoluto del radio de la diferencia entre las coordenadas de x de inicio y final. Luego, dentro de un ciclo for el cual se ejecuta 360 veces, se aplica hacia adelante la fórmula de la circunferencia del círculo dividida entre 360 y se gira un grado en cada iteración del ciclo para formar el círculo. Al finalizar, la figura se rellena del color asignado por el usuario previamente.