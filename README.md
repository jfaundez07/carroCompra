## Joaquin Faundez
Tarea receso " Análisis de código & Dependencia "

# i. Identifique las clases y lo que éstas representan. Luego, establezca una descripción textual breve del contexto problema.
Tiene dos clases, Calculadora y carroCompra, que simulan como lo dicen sus nombres, una calculadora que suma y multiplica, y un carro de compra de algo que podría ser un supermercado que almacena la cantidad y precio de los productos que se lleva, respectivamente.
# ii. Analice los atributos y métodos de cada clase, luego, identifique las relaciones existentes entre las clases identificadas y establezca una descripción textual breve del contexto problema..
Clase calculadora: como lo dice su nombre, es una calculadora que se encarga de sumar y multiplicar dos números de tipo entero que corresponden a los atributos de la clase. Tiene un constructor vació que inicializa dichos atributos en 0, y otro que utiliza dos parámetros ingresados. Posee 2 métodos principales, sumar y multiplicar que retorna la suma y la multiplicación respectivamente de sus atributos, ademas de sus set para ambos atributos.

Clase CarroCompra: simula un carro de supermercado con productos representado por su único atributo el cual es una matriz de 2 filas y 5 columnas, siendo la fila 0 la cantidad que se quiere comprar de un producto, y la fila 1, el precio de dicho producto. Todo esto es definido en el constructor de la clase. Luego tiene un método “subTotal” que se encarga de instanciar un objeto de tipo Calculadora con 2 parámetros, y retorna el método multiplicar de la clase mencionada con dichos parámetros. subTotal es utilizado en el método calcularTotal, que le entrega como parámetros, la cantidad y el precio de un producto, y va almacenando en una variable local, la suma de las multiplicaciones. Finalmente tiene un metodo mostrarTotal que llama al método calcularTotal,que muestra el precio total de los producto en el carro.

# iii. De lo anterior, establezca una representación detallada del código fuente, usando un diagrama de clases UML y la herramienta de modelado Visual Paradigm.
![Captura desde 2023-10-11 15-07-14.png](..%2F..%2F..%2F..%2FIm%C3%A1genes%2FCapturas%20de%20pantalla%2FCaptura%20desde%202023-10-11%2015-07-14.png)
# Imagen estructura del proyecto IDE local: 
![Captura desde 2023-10-11 15-15-37.png](..%2F..%2F..%2F..%2FIm%C3%A1genes%2FCapturas%20de%20pantalla%2FCaptura%20desde%202023-10-11%2015-15-37.png)
# Imagen compilacion exitosa: 
![Captura desde 2023-10-11 15-16-03.png](..%2F..%2F..%2F..%2FIm%C3%A1genes%2FCapturas%20de%20pantalla%2FCaptura%20desde%202023-10-11%2015-16-03.png)

