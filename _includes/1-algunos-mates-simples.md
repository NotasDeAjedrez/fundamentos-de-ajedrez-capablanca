# Primera Parte - Los principios del ajedrez

# Capítulo 1 - Primeras nociones: finales, mediojuego y aperturas

Lo primero que debe hacer el estudiante es familiarizarse con el poder de las
piezas. Ello se obtendrá de la mejor manera aprendiendo como dar rápidamente
algunos de los mates más simples.

## 1. Algunos mates simples

### Ejemplo 1°.- Mate de torre y rey contra rey.

La regla consiste en llevar al rey adversario hasta el borde, en cualquier lado del
tablero.
<figure>
    <chess-board
        position="7k/8/8/8/8/8/8/R6K w - - 0 1">
    </chess-board>
    <figcaption>
    <a href="https://lichess.org/analysis/7k/8/8/8/8/8/8/R6K_w_-_-_0_1?color=white">Tablero de análisis</a>
    <br>
    Juegan blancas
    </figcaption>
</figure>

En esta posición el poder de la torre queda demostrado con la primera jugada, **1.
Ta7**, que de inmediato recluye al monarca adversario a la última fila, y entonces el
mate se obtiene con toda rapidez, por medio de: **1. Ta7 Rg8 2. Rg2**. La acción
combinada del rey y la torre es necesaria para obtener una posición en la cual pueda
forzarse el mate. La regla general que debe observarse es la siguiente: Conservar el
rey todo lo posible, en la misma fila o, como sucede en el ejemplo que estamos
examinando, en la misma columna que el monarca adversario. Como en nuestro caso
el rey conseguirá llegar a la sexta fila, lo mejor es colocarlo en la columna más
cercana y hacia el centro.

**2. … Rf8 3. Rf3 Re8 4. Re4 Rd8 5. Rd5 Rc8 6. Rd6**
Y no 6. Rc6, en razón de que en tal caso el rey negro volvería a d8 y se dilataría la
obtención del mate. Si ahora el rey se mueve a d8, Ta8 da mate en seguida.

**6. … Rb8 7. Tc7 Ra8 8. Rc6 Rb8 9. Rb6 Ra8 10. Tc8 mate.**
Fueron necesarias exactamente diez movidas para conseguir dar mate a partir de
la posición del ejemplo. En su quinta movida, las negras pudieron haber jugado Re8
y, en consonancia con la regla, entonces las blancas Debían haber continuado con 6.
Rd6 Rf8 (el rey negro será, por último, forzado a colocarse frente al rey blanco y el
mate se conseguirá por medio de Ta8) 7. Re6 Rg8 8. Rf6 Rh8 9. Rg6 Rg8 10. Ta8
mate.

### Ejemplo 2°.- Mate de torre y rey contra rey.

<figure>
    <chess-board
        position="8/8/8/4k3/8/8/8/4K2R w - - 0 1">
    </chess-board>
    <figcaption>
    <a href="https://lichess.org/analysis/8/8/8/4k3/8/8/8/4K2R_w_-_-_0_1?color=white">Tablero de análisis</a>
    <br>
    Juegan blancas
    </figcaption>
</figure>

Como en este ejemplo el rey negro se halla situado en el centro del tablero, el
mejor procedimiento consiste en avanzar con el nuestro en la siguiente forma:

**1. Re2 Rd5 2.Re3**. No habiendo la torre aún entrado en juego, lo mejor es
avanzar con el rey hacia el centro del tablero, y no frente al adversario, sino a un
costado del mismo, de modo que si ahora el rey negro juega a **e5**, la torre lo hará
retroceder mediante **Th5+**. Por otra parte si **2. … Rc4**, también **3. Th5**. Si ahora **3. …
Rb4.** seguiría **4. Rd3**; pero, si en lugar de esto se jugara **3. … Rc3** entonces **4. Th4**,
recluyendo al monarca adversario a la menor cantidad de escaques que pueda tener a
su disposición. Ahora el final puede continuarse con **4. … Rc2 5. Tc4+ Rb3 6. Rd3
Rb2 7. Tb4+ Ra3 8. Rc3 Ra2**. Aquí deberíamos observar que a menudo el rey
blanco se ha movido al lado de la torre, con el propósito no sólo de apoyarla, sino
también de reducir la movilidad del rey oponente. En esta posición las blancas
obtienen el mate en tres jugadas: **9.Ta4+ Rb1 10.T** juega a cualquier casilla en la
columna a, forzando al rey negro a colocarse en c1, es decir frente al rey blanco, y,
entonces, **11. Ta1 mate**. Han sido necesarias once movidas para la obtención del
mate, y creo que podría conseguirse este resultado, cualquiera fuera la posición que
se presente, en menos de veinte. Aunque resulte una tarea monótona, es muy
conveniente para el iniciado practicar muchas veces estas posiciones, hasta conseguir
dominarlas sin esfuerzo.

### Ejemplo 3°.- Mate de rey y dos alfiles contra rey.

Ya que el rey negro se halla ubicado en uno de los ángulos del tablero, las blancas
pueden jugar **1. Ad3 Rg7 2. Ag5 Rf7 3. Af5** y tenemos que al adversario le restan
pocas casillas a su disposición. Si el monarca negro, en la posición original, se hallara
situado en el centro del tablero, o en alguna casilla que no fuera angular, las blancas
deben avanzar su rey y luego, con ayuda de los alfiles, limitar sus movimientos al
menor número de escaques posible.

<figure>
    <chess-board
        position="7k/8/8/8/8/8/8/2B1KB2 w - - 0 1">
    </chess-board>
    <figcaption>
    <a href="https://lichess.org/analysis/7k/8/8/8/8/8/8/2B1KB2_w_-_-_0_1?color=white">Tablero de análisis</a>
    <br>
    Juegan blancas
    </figcaption>
</figure>

Ahora podemos continuar en la siguiente forma: **3. … Rg7 4. Rf2**. En este final el
rey negro no sólo debe ser llevado hasta el borde del tablero, sino, además, reducido a
una casilla angular y, antes que pueda darse mate, debe colocarse el rey blanco en la
sexta fila, y al propio tiempo, en una de las dos columnas finales del tablero. De
manera que el monarca blanco debe avanzar hasta colocarse en las casillas **h6, a6, g6,
b6, f7, c7, f8 o c8**, puesto que tal colocación es la más próxima, siguiendo lo
establecido en la regla enunciada.

**4. … Rf7 5. Rg3 Rg7 6. Rh4 Rf7 7. Rh5 Rg7 8. Ag6 Rg8 9. Rh6 Rf8.**
Las blancas deben ahora ganar tiempo moviendo uno de sus alfiles, de tal modo
que obliguen al rey negro a retroceder;

**10. Ah5 Rg8 11. Ae7 Rh8.**
En este momento el alfil que corre por casillas blancas tiene que ser colocado en
una posición que lo habilite a dar jaque en el golpe siguiente, a lo largo de la diagonal
de su color, al mover el oponente a g8. Por ejemplo:

**12. Ag4 Rg8 13. Ae6+ Rh8 14. Af6 mate.**
Han sido precisos catorce movimientos para poder obtener una posición de mate,
y estimo que, en cualquier posición que pudiera presentarse, este resultado debe ser
alcanzado en un número menor de treinta. En todos los finales de este tipo debe
tenerse sumo cuidado en no llegar a una posición de «ahogado», que haría tablas el
cotejo y, por consiguiente, esfumaría la obtención de la victoria.

En este caso particular hay que recordar que el rey adversario, no sólo tiene que
ser recluido al borde del tablero, sino que, al propio tiempo, a uno de los ángulos del
campo de lucha. No obstante, en todos estos finales no tiene mayor importancia que
el rey negro sea forzado a retirarse a la última fila o a la última columna del tablero.
Por ejemplo, tanto valdría obligarlo a colocarse en las casillas **h5, a4, e1 o d8**.

### Ejemplo 4°.- Mate con rey y dama contra rey.

Como la dama suma el poder de acción de torre y alfil combinados; resulta que estamos en presencia del más fácil de todos los mates; en este caso debería siempre obtenerse en menos de diez jugadas.

<figure>
    <chess-board
        position="8/8/8/4k3/8/8/8/4K2Q w - - 0 1">
    </chess-board>
    <figcaption>
    <a href="https://lichess.org/analysis/8/8/8/4k3/8/8/8/4K2Q_w_-_-_0_1?color=white">Tablero de análisis</a>
    <br>
    Juegan blancas
    </figcaption>
</figure>

En la presente posición, una excelente forma de iniciar las acciones consiste en
tratar de limitar la movilidad del rey negro todo lo más que sea posible. Por ejemplo:
**1. Dc6 Rd4 2. Rd2**. Ahora lo tenemos reducido a la sola posibilidad de ocupar una
casilla **2. … Re5 3. Re3 Rf5 4. Dd6 Rg5** (si las negras hubiesen jugado Rg4,
entonces 5. Dg6+) **5. De6 Rh4** (si Rh5 Rf4 y mate en la próxima movida) **6. Dg6
Rh3 7. Rf3, rey mueve**; la dama da mate en varias casillas.

En este final, como también en el de rey y torre contra rey, el monarca negro debe
ser llevado a uno de los bordes del tablero, pero como la dama posee mucho más
poder de movilidad que la torre, el proceso resulta también mucho más fácil y corto.
Estos son los tres finales elementales y en ellos el principio es el mismo. En cada
uno de los casos, la cooperación del rey se hace imprescindible. Para poder obtener
una posición de mate sin la intervención del rey es preciso por lo menos la acción de
dos torres.