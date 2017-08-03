# GUIÓN HABLADO

### Toma 0:

"A continuación introduciremos una notación que aún no está en el apunte pero nos será útil". 

### Toma 1:

* "Probaremos un resultado general que nos enseñará a simular el comportamiento de un programa con una máquina de Turing. Es importante notar que la simulación que nos interesa que haga la máquina simuladora no es a nivel de la función que computa el programa sino a un nivel más general, es decir, nos interesa que simule a dicho programa como transformador de estados".

* "La máquina simuladora que construiremos simulará a $\mathcal{P}$ en cuanto a
su funcionamiento cuando partimos de estados de la anterior forma".

* "(que son infinitos ya que la cinta es infinita hacia la derecha)"

### Toma 2:

* "Cada una de las cuales simularán, vía la representación anterior, el funcionamiento de las distintas instrucciones de $\mathcal{P}$".

* "Esto simplificará un poco la costrucción de la máquina simuladora y de hecho lo podemos hacer, ya que toda función $\Sigma$-computable puede ser computada por un programa sin este tipo de 	instrucciones, tal como lo veremos en un lema más adelante".

* "Esta propiedad es importante ya que nos permitirá concatenar pares de dichas máquinas identificando algún estado final de la primera con el inicial de la segunda".

### Toma 3:

* "Que se corresponde con las descripciones instantaneas de la computación anterior"

### Toma 4:

* "Ahora describiremos en general como puede armarse la máquina simuladora de $\mathcal{P}$, respecto de $k$. Para poder hacer concretamente las máquinas recién descriptas deberemos diseñar antes algunas máquinas auxiliares".

### Toma 5:

* "A continuación enunciaremos en forma de lema la existencia de la
máquina simuladora y de las propiedades escenciales que usaremos luego para
probar que toda función $\Sigma$-computable es $\Sigma$-Turing computable".

### Toma 6:

* "En esta etapa nos dedicaremos a explicar como construir las distintas máquinas simuladoras de instrucciones".

* "Es decir la máquina D_{j} lo único que hace es mover el cabezal desde el blanco de la izquierda de un bloque determinado, exactamente j bloques a la derecha".

* "Análogamente $I_{j}$ será una máquina que desplaza el cabezal $j$ bloques a
  la izquierda del blanco que esta escaneando". 
  
* "Es decir la máquina $TD_{j}$ corre un espacio a la derecha todo el segmento $\gamma $ y agrega un blanco en el espacio que se genera a la izquierda".

* "Es decir la máquina $TI_{j}$ corre un espacio a la izquierda todo el segmento $\gamma$ (por lo cual en el lugar de $\sigma$ queda el primer símbolo de $\gamma $)". 

### Toma 7:

* "Es fácil ver que $\mathcal{Q}$ tiene las propiedades (1) y (2)".

* "Por supuesto, hay un lema análogo para el caso en que $f$ llega a $\omega$
en lugar de llegar a $\SIGMA$".

* "Ahora si, el anunciado del teorema":

* "A continuacion veremos que $M$ computa a $f$".

* "(vía la copia de $M_{1}$ dentro de $M$)... (ya que $M$ es determinística)".

* "(ahora vía la copia de $M_{sim}$ dentro de $M$)".