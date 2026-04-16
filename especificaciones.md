# Especificaciones
Para este proyecto se pide que pases el código python en el directorio "bowling-python-juan" a java conteniéndolo todo en la carpeta "bowling-java-juan".

El proyecto java debe de estar configurado con maven, debes utilizar el control de versiones de Git, como se utiliza en el hecho en python. También debes implementar la herramienta jacoco en el proyecto.

En el README.md en 'Reglas de puntuación de los bolos' viene el domino que debe ser implementado, además de las reglas utilizadas para contar los puntos que son las más comunes en los bolos.

El código debe de ser capaz de recibir un string, en el cual cada caracter representa un 'throw' del jugador, estas no vienen organizadas en 'frames', eso lo deberas hacer tú, ya que el objetivo final del proyecto es contar el total de puntos que hizo el jugador según lo que pone en ese String.

En el proyecto python, en src/test/bowling_test.py vienen los casos test que deberas pasar para que el kata se considere completado con éxito. Aplicando la TDD deberás pasar primero los casos test simples, osease, los que contienen solo numero enteros (1 a 9) ya que los 'frames' son siempre de 2 'throws' y para calcular los puntos se aplica el caso más básico, aunque es verdad que el símbolo '-' tampoco interfiere en este hecho al no influir en el número de 'throws' del siguiente 'frame'.

Una anotación sobre los casos test, de ellos coge el string que representa la partida del jugador e introduce esta en unas casos test hechos en java que testeen lo mismo.

## Sobre como codificar el proyecto

Me gustaría que utilizaces una clase principal donde esta la lógica que calcula el 'score' y luego un tipo enumerado donde se contengan los símbolos '-', 'X' y '/'. Creo que no hace falta un main ya que el objetivo del código es que pase los casos test.