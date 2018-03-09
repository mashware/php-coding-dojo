# Kata Minesweeper

¿Alguna vez has jugado al buscaminas? Es un divertido juego que viene incluído en un determinado sistema operativo cuyo nombre no puedo recordar. Pues bien, el objetivo del juego es encontrar todas las minas dentro de un campo M x N. para ayudarte, el juego muestra en cada celda sin mina un número que te dice cuántas minas hay adyacentes a la celda. Por ejemplo, tomemos el siguiente campo de 4x4 con 2 minas (representadas por un carácter '*'):
```
*...
....
.*..
....
```

El mismo campo de minas pero con los números de minas adyacentes, se vería así:
```
*100
2210
1*10
1110
```

## Enunciado
Debes escribir un programa que tome como entrada lo siguiente:

Un úmero arbitrario del número de filas y columnas del campo de minas. La primera línea de cada campo de minas contiene 2 enteros n (filas) y m (columnas) (0 < n, n <= 100) que representan el número de filas y columnas del propio campo. Las siguientes n filas contienen exactamente m caracteres y representan cada celda de la fila. Cada celda sin mina se representa por el caracter '.' (sin las comillas) y cada celda con mina con un carácter '*' (también sin comillas). La primera línea donde n = 0 y m = 0 representan el final de la entrada y no debe ser procesada.

Tu programa debe producir una salida como la siguiente:
```
Campo #x:
<campo de minas>
```

Donde x es el número del campo de minas (comenzando en 1). Las siguientes n filas deben contener el propio campo de minas representado con '*' las celdas con mina y con número de minas adyacentes las celdas sin minas. 
Todo esto, deberás repetirlo por cada campo de minas definido en la entrada del usuario.
Debe haber una línea en blanco entre cada campo de minas.

Pista
Como habrás notado, cada celda puede tener un máximo de 8 celdas adyacentes.
## Test de aceptación sugerido
La entrada:
```
4 4
*...
....
.*..
....
3 5
**...
.....
.*...
0 0
```
y la salida:
```
Campo #1:
*100
2210
1*10
1110
```
```
Campo #2:
**100
33200
1*100
```
##Acerca de la kata
* Kata original: http://acm.uva.es/p/v101/10189.html
* Fuente original: http://codingdojo.org/cgi-bin/wiki.pl?KataMinesweeper