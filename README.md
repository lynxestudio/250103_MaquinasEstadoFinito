# Notas acerca de las maquinas de estado finito.

<h2>Que son las maquinas de estado finito?</h2>
<p align="justify">
Consiste en un modelo del comportamiento de un sistema. Este modelo tiene una cantidad <strong>finita</strong> de posibles <strong>estados</strong> y el sistema puede cambiar de estado cuando se cumple una <strong>condicion de transicion</strong>. Cada uno de los estados determina el tipo de accion que la maquina lleva a cabo. Una transicion indica el cambio de estado.
</p>
<p>
Para representar estas maquina usamos un diagrama de estados en donde los estados se representan por circulos, colocando el nombre del estado en su interior. Por medio de flechas, indicamos las transiciones entre los estados. Estas flechas llevan un rotulo que indica la condicion de transicion. Los estados estan numerados y en su interior pueden indicarse las acciones que ejecutan.
</p>
<p>
Una de las maquinas de estados finitos mas conocidas de la historia es la maquina de Turing, creada en 1936. Esta maquina es una maquina de estados finitos muy simple, pero con la capacidad de simular la logica de cualquier computadora.
</p>
<img src="" alt="">
<p>
La maquina de estados finitos permanecera en el mismo estado hasta que se lleve a cabo una transicion. Mientras se encuentra en ese estado, llevara a cabo una accion.
Hay cuatro tipos basicos de acciones: de entrada, de salida, de ingreso y de transicion.
</p>
<p>
Cuando se llega a un nuevo estado y se ejecuta una accion, a esta se le conoce como <strong>accion de ingreso</strong>. Es lo primero que se hace cuando llegamos al nuevo estado. Si tenemos que llevar a cabo una accion al salir de un estado, decimos que esa accion es una <strong>accion de salida</strong>.
</p>
<p>
Frecuentemente, nos encontramos con que el sistema recibe una entrada y debemos llevar a cabo una accion. Esta accion se conoce como <strong>accion de entrada</strong>, y dependera de la entrada que recibimos y del estado en el cual se encuentre la maquina en ese momento. Si fuera necesario que la accion se llevara a cabo durante una transicion, entonces la accion se conoce como <strong>accion de transicion</strong>.
</p>
<p>
Las maquinas de estados finitos se clasifican en dos grupos:
<ol>
<li><strong>Reconocedores:</strong> se caracterizan por su salida binaria, falso o verdadero como salida.</li>
<li><strong>Transductores:</strong> estos nos dan una salida que depende de su entrada, y el estado, con sus acciones.</li>
</ol>
</p>
<p>
Los transductores se utilizan principalmente en aplicaciones de control; existen diferentes tipos de transductores, pero los mas basicos son la maquina de <strong>Moore</strong> y la maquna de <strong>Mealy</strong>.
En la maquina de Moore, la salida dependera del estado en el que se encuentra la maquina, y en la maquina de Mealy, la salida dependera del estado que se encuentra la maquina màs la entrada.
</p>
<p>
Ademas de utilizar diagramas para las maquinas de estados finitos existe la posibilidad de usar una <strong>tabla de transicion de estados</strong>. En esta tabla podemos indicar los estados, las condiciones de transicion y las acciones.
</p>
<p>
Existen diversos tipos de tablas de transicion, en este caso una tabla donde los estados se colocan en el eje horizontal y el eje vertical. El eje vertical indicara el estado actual en el que se encuentra la maquina y en el estado horizontal, el estado al cual se dirigira despues de la transicion. En las celdas de la tabla, colocaremos la condicion de transicion. Si algun estado no tiene transicion hacia otro estado, entonces, en la celda se coloca una linea horizontal para indicar que no hay transicion.
</p>