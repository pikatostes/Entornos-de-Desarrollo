# HERRAMIENTAS DE DESARROLLO

#### 2. Para cada uno de los lenguajes anteriores, indica el proceso realizado  para conseguir ejecutar el código: ¿compilación o interpretación?

- Bash: intérprete
- Python: interpretado
- JavaScript: interpretado
- C: compilados
- Java: compilados
- Ensamblador:



#### 3. Para cada uno de los lenguajes anteriores, indica el nombre del compilador o interprete utilizado en GNU/Linux.

- Bash: SHELL



#### 4. Investiga y averigua que extensión tienen los archivos de código fuente de los siguientes lenguajes:

- Bash: .sh
- Python: .py
- PHP: .php
- JavaScript: .js
- C: .c
- C++: .cc
- Java: .java
- Ensamblador: .asm
- Ruby: .ruby
- Go: .go
- Rust: .rs 
- Lisp: .lisp



#### 5. Scripts ejecutables para los lenguajes interpretados. Edita los scripts para los siguientes lenguajes:

- 



#### 6. ¿Qué extensión tienen los archivos de código objeto?

- Los archivos de código objeto tienen la extension ".obj".



#### 7. Lenguaje C. Código en varios archivos. Obtener el código objeto a partir del código fuente:

#### 8. Lenguaje C. Código en varios archivos. Obtener el código binario  ejecutable a partir del código objeto de los 3 archivos anteriores:

<img src="Tema 2/Herramientas de Desarrollo/cap-ej7.png">

#### 9. Lenguaje C++. Código en varios archivos. Obtener el código objeto a partir del código fuente de los 3 archivos siguientes:

#### 10. Lenguaje C++. Código en varios archivos. Obtener el código binario  ejecutable a partir del código objeto de los 3 archivos anteriores:

<img src="/home/alejandro/Escritorio/en-ds/herramientas/cap-ej9.png">



#### 11. Bibliotecas. Define que se entiende por biblioteca o librería y los tipos que existen.

- Conjunto de archivos objeto que extienden la funcionalidad del lenguaje



#### 12. Bibliotecas. ¿Qué tipo es el más utilizado actualmente? ¿Por qué?

- Las bibliotecas dinámicas. Porque facilitan la gestión y aprovechamiento de la memoria del sistema: La carga dinámica permite al sistema operativo aplicar algoritmos que  mejoren el rendimiento del sistema cuando se carguen estas bibliotecas.  Además, al estar compartidas, basta con mantener una copia en memoria  para todos los programas que la utilicen.

  

#### 13. Bibliotecas. Crea una biblioteca dinámica en C que proporcione las  funciones para sumar, restar, multiplicar y dividir 2 números enteros. Crea un programa que haga uso de ella y comprueba que se ejecuta  correctamente.

- 



#### 14. Bibliotecas. Busca información y explica las ventajas y desventajas de usar bibliotecas estáticas.

#### 15. Bibliotecas. Busca información y explica las ventajas y desventajas de usar bibliotecas estáticas.

- Un programa compilado con librerías estáticas es más grande, ya que se hace copia de todo lo que necesita.
- Un programa compilado con librerías estáticas se puede llevar a otro ordenador sin necesidad de llevarse las librerías.
- Un programa compilado con librerías estáticas es, en principio, más rápido en ejecución. Cuando llama a una función de la librería, la tiene en su código y no tiene que ir a leer el fichero de la librería dinámica para encontrar la función y ejecutarla.
- Si cambiamos una librería estática, a los ejecutables no les afecta. Si cambiamos una dinámica, los ejecutables se ven afectados. Esto es una ventaja si hemos cambiado la librería para corregir un error (se corrige automáticamente en todos los ejecutables), pero es un inconveniente si tocar eso nos hace cambiar los ejecutables (por ejemplo, hemos añadido un parámetro más a una función de la librería, los ejecutables ya hechos dejan de funcionar).
