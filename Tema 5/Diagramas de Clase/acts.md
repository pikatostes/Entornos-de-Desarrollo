# ACTIVIDADES UNIDAD 5: DIAGRAMAS DE CLASES

## UML

### 1. ¿Qué significan las siglas UML? Busca información acerca de su historia y las versiones que han existido y el año de publicación.

UML se refiere a Lenguaje de Modelado Unificado, el cual fue creado por expertos en modelado de objetos en la década de 1990 con la intención de brindar un lenguaje común para describir y representar sistemas de software. La primera versión de UML fue publicada en 1997 y ha habido una serie de actualizaciones desde entonces, incluidas UML 1.x, UML 2.0, UML 2.1, UML 2.2, UML 2.3, UML 2.4 y UML 2.5.

### 2. Indica los tipos de diagramas de estructura que existen en UML.

En UML, los diagramas de estructura incluyen el Diagrama de Clases, el Diagrama de Objetos, el Diagrama de Componentes, el Diagrama de Paquetes, el Diagrama de Estructura de Componentes, y el Diagrama de Composición.

### 3. Indica los tipos de relaciones que pueden darse y explica brevemente.

Los diagramas de comportamiento incluyen el Diagrama de Secuencia, el Diagrama de Colaboración, el Diagrama de Estados, el Diagrama de Actividades, el Diagrama de Casos de Uso, y el Diagrama de Interacción.

## DIAGRAMAS DE CLASES

### 1. Siguiendo la notación UML, pon 2 ejemplos de clases distintos a los vistos en este tema.

1. Clase "Producto"
   - Atributos: idProducto, nombre, descripcion, precio, stock
   - Métodos: agregarStock(int cantidad), disminuirStock(int cantidad), calcularPrecioOferta(float descuento)
2. Clase "OrdenDeCompra"
   - Atributos: idOrden, fecha, proveedor, total
   - Métodos: agregarProducto(Producto p, int cantidad), eliminarProducto(Producto p), calcularTotal(), enviarOrden()

### 2. Siguiendo la notación UML, pon 2 ejemplos de interfaces distintos a los vistos en este tema.

1. Interfaz "Pagar"
   - Métodos: realizarPago(float monto), obtenerTotal(), cancelarPago()
2. Interfaz "Autenticar"
   - Métodos: iniciarSesion(String usuario, String contraseña), cerrarSesion(), cambiarContraseña(String nuevaContraseña)

### 3. Indica los tipos de relaciones que pueden darse y explica brevemente.

1. Asociación: Es una relación básica que indica que dos elementos están relacionados de alguna manera. Se puede especificar la multiplicidad, que indica cuántos objetos de cada clase pueden estar relacionados.
2. Herencia: Es una relación en la que una clase hereda atributos y métodos de otra clase (clase padre). La clase que hereda se conoce como clase hija o subclase.
3. Dependencia: Es una relación en la que un elemento de modelo depende de otro elemento para su especificación o implementación. Por ejemplo, una clase puede depender de una interfaz para implementar sus métodos.
4. Agregación: Es una relación de tipo "todo-parte" en la que una clase contiene una colección de objetos de otra clase, pero los objetos pueden existir fuera de la clase contenedora.
5. Composición: Es una relación similar a la agregación, pero los objetos de la clase contenida son parte integral de la clase contenedora y no pueden existir fuera de ella.
6. Realización: Es una relación en la que una clase implementa los métodos de una interfaz.
7. Generalización: Es una relación entre dos elementos de modelo, donde uno es un caso especial del otro. En otras palabras, una clase más general puede ser especializada en una subclase más específica.