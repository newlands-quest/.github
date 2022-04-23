# New Lands Quest

Game design document. 

* Autor: [/EnzoDiazDev](https://github.com/enzodiazdev)
* Versión: 1.0 - 17/04/2022

> El documento se encuentra atado a modificaciones futuras.
> Corroborar la versión.

## Índice

* [Ficha Técnica](#ficha tecnica)
* [Influencias](#influencias)
* [El juego](#el juego)

## Ficha técnica

* **Motor gráfico**: HTML5.
* **Estilo gráfico**: Texto interactivo.
* **Protocolo**: WebSockets.
* **Género**: Rol, supervivencia, gestión de recursos.
* **Ambientación**: Feudal, reinos.

## Influencias

El desarrollo de este juego toma como principal influencia al equipo de [Motion Twin](http://motion-twin.com), una cooperativa francesa responsable de Muxxu y Twinoid, las plataformas donde distribuían los juegos que New Lands Quest toma como inspiración. 

Tras el cierre y desuso de Adobe Flash Player, estos juegos se encuentran abandonados y no se pueden jugar.

### - Kingdom

Kingdom es un juego multijugador de gestión y conquista donde compites con otros jugadores.<br>
Debes producir recursos en tu capital, reclutar soldados y expandir tu reino, y así convertirte en un gran Emperador.

El juego consta de un gran mapa con distintas ciudades, cada jugador es dueño de la suya, su capital. En ésta obtienes tus recursos mediante un tablero de "match tres", moviendo dos recursos adyacentes para formar una fila o columna de al menos 3 recursos iguales.

Los recursos son utilizados para construir armas y defensas para invadir otros reinos, avallasando a otros jugadores para crecer tu reino.<br>
El juego cuenta con mecánicas de amistad y enemistad, ofreciendo un fuerte apartado de juego de rol para convencer a otros jugadores a unirse a tu reino o declararle la guerra. 

New Lands Quest no solo toma la temática medieval de Kingdom, sino también el sistema de reinos y conquista, así como la gestión de recursos y economía.

### - Zombinoia (Hordes)

Zombinoia es un juego de estrategia donde cooperas con otros 40 jugadores en un pueblo. El objetivo es cooperar con tus compañeros y sobrevivir la mayor cantidad de días posibles. 

Cada día, se debe salir al desierto en busca de materiales para construir defensas y regresar antes de la media noche, horario en el que los zombies atacan el pueblo. <br>
Si tu pueblo cuenta con el numero de defensas suficientes, sobrevivirán. 

En Zombinoia existen muchas micromecánicas y distintos peligros.<br>
Cada día, el jugador cuenta con 6 puntos de acción que podrá recuperar bebiendo, comiendo o estimulándose con sustancias. <br>
Algunos jugadores llamados "héroes" cuentan con habilidades especiales que dan grandes ventajas al pueblo en términos de defensa, exploración, construcción, etc. 

También ofrece muchas mecánicas de rol, como atacar a tus compañeros, desterrarlos del pueblo, acampar en el desierto, robar objetos, explorar ruinas, etc. 

New Lands Quest toma principalmente las mecánicas de Zombinoia.

### - Dead Cells (el original)

Dead Cells, fue el *sucesor espiritual* de Zombinoia.<br>
Fue anunciado el 2 de Septiembre de 2014, aunque su diseño original fue cancelado y nunca salió.<br>
*En su lugar, Motion Twin decidió convertirlo en un roguelite que fue lanzado para Steam en 2018, convirtiéndose en un auténtico éxito con millones de ventas y decenas de premios en distintas categorías.* 

El juego original, fue una especie de Tower Defense, algo similar a los pueblos de Zombinoia, pero en este caso son castillos. <br>
En cada castillo hay equipos de 8 personas y el objetivo es sobrevivir a los ataques de los zombies. <br>
Para hacerlo, se pueden construir defensas: puertas, barricas y más cosas que sirvan para proteger el castillo. Según cierta información de los creadores, durante el juego habría rondas de 1 hora para preparar las defensas.<br>
También existen armas, estas se pueden encontrar excavando, o comprándoselas a un mercader que vive en el bosque. Existen armas como ballestas, arcos, torretas, entre otras. 

La parte innovadora y emocionante del diseño original era la "coopetición". 

> Cooperación + competición. Todos están obligados a ayudarse mutuamente y al mismo tiempo todos compiten para ser el último superviviente. 	

Esto permitía que los jugadores se vean obligados a realizar distintas estrategias para traicionar y utilizar a sus compañeros para ganar.

### - MUDs

Un MUD es un juego multijugador en tiempo real en un mundo virtual, por lo general en modo texto. Los MUDs combinan elementos de videojuego de rol, hack and slash, jugador contra jugador, ficción interactiva, y chat.<br>
Los Jugadores pueden leer, ver u oír las descripciones de las salas, objetos, otros jugadores, NPCs, y acciones realizadas en el mundo virtual. <br>
Los Jugadores generalmente interactúan entre ellos en el mundo escribiendo comandos similares al lenguaje natural. 

New Lands Quest cabe perfectamente en la definición de MUD

El ejemplo más acertado es Genesis MUD, actualmente jugable a través de [genesismud.org/play](https://www.genesismud.org/play/).<br>
Génesis es un juego de rol gratuito basado en texto, ambientando en un enorme mundo de fantasía. <br>
Cuenta con más de 10 razas y subrazas diferentes, que determinan la historia detrás de quién eres y en quién elegirás convertirte.<br>
Podrás explorar más de 20 reinos únicos y cumplir cientos de misiones hechas a mano repartidas por todo el juego, obteniendo objetos y generando riquezas. <br>
Determina tu papel en los reinos eligiendo una profesión que te brindará un propósito, poder y una profunda historia. 

La jugabilidad de Génesis es lo más cercano a la jugabilidad esperada para New Lands Quest, añadiendo aún más interactividad en su interfaz. 

## El juego

New Lands Quest es un MMORPG basado en comandos. 

El mundo se encuentra gobernado enteramente por la Gran Reina. <br>
Los ciudadanos, hartos de no tener voz ni voto, deciden reclamar una tierra y formar grupos rebeldes con un autoproclamado Monarca del nuevo reino. 
La Gran Reina es consciente de la actividad rebelde, pero reconoce que ya no puede gobernar sin ayuda. Para elegir el reino más fuerte, decide poner en conflicto a los distintos grupos rebeldes y enviar tropas reales al ataque hasta que solo quede uno en pie. 

El monarca rebelde deberá liderar a sus fieles quienes tendrán distintas habilidades y responsabilidades según se considere necesario. <br>
Los ciudadanos del nuevo reino deberán recolectar materiales, reclutar soldados y negociar para hacer prosperar el reino. <br>
El reino enfrentará dificultades climáticas, de escasez de recursos, ataques de reinos enemigos o del ejército de la Gran Reina y hasta la traición de sus propios ciudadanos.

### Jugabilidad

New Lands Quest es sencillo.<br>
Mediante un input interactivo ingresaremos los comandos para realizar consultas y acciones.

Las consultas son todos aquellos comandos que comiencen por `?`, mientras las acciones son aquellos que comienzan por `!`. <br>
`?me`<br>
`— Te llamas ..., estás en un enorme campo fértil y...`

`!chop`<br>
`— Con todas tus fuerzas golpeas el árbol hasta conseguir algo de leña... `

A su vez, se planea agregar un comando de roleplay para introducir diálogos por parte de los jugadores, utilizando el prefijo `>`. <br>
`> Deberíamos ir a recolectar recursos! `<br>
`Fulano: Deberíamos ir a recolectar recursos!`

### Inicio

Cuando el jugador ingresa al juego, se encuentra con un universo ya comenzado y constante evolución. <br>
Ya sea como Monarca o ciudadano, el jugador deberá evaluar la situación del reino para comenzar a tomar decisiones. 

En cuanto el jugador se conecta a la partida, deberá conocer a su rey y/o a sus compañeros, generalmente en un reino de hasta 5 jugadores.<br>
Una vez puesto al tanto de la situación, el jugador deberá adaptarse para realizar su aporte a la prosperidad del reino; seleccionando un rol, buscando recursos, construyendo edificios, explorando el área, etc.

### Progresión

Debido a que no hay un inicio concreto ni un final, el juego cuenta con micromecánicas que permitirán progresar y acercarse al objetivo de ser el reino más grande de New Lands. 

El juego transcurre en tiempo real, 24/7. 

### Mecánica principal

El juego tendrá un horario real (UTC), que incluirá en su momento estaciones y diferentes climas, edad del jugador, ciclos de cosecha, etc. <br>
Cada noche (23:55 a 00:05 UTC), el juego queda inhabilitado durante el ataque de los soldados de la Gran Reina. 

Durante el día, el equipo deberá recolectar recursos para su propia supervivencia y defensas para el reino. 

A medida que un reino avance ganará puntos (según dinero, recursos, habitantes, defensas, etc.), y se calculará un ataque proporcional a su progreso del cual tendrán que defenderse. 

