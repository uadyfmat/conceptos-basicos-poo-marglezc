[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ytCADFsI)

# Preguntas examen
## Diferencia entre Clase y Objeto
En la programación orientada a objetos, una clase es una plantilla o modelo para crear objetos. Una clase define un conjunto de atributos y métodos que los objetos pueden tener, en cambio un objeto es es una instancia concreta de la clase con un estado y comportamiento específico.
## Diferencia entre Clase e Interfaz
La diferencia es que una clase es una estructura que define atributos y comportamientos de un objeto mientras que una interfaz indica qué métodos debe implementar una Clase aunque no tienen por qué comportarse del mismo modo. 
## Qué es polimorfismo? Ejemplo con tu proyecto
Es cuando una referencia se puede comportar como el objeto al que apunta, un ejemplo de esto en nuestro proyecto sería la funcion guardar depende si lo usa un maestro o administrador, en el primer caso imprimiría que no se puede hacer, en el segundo funcionaría normalmente.
## Qué representan las asociaciones en un DC? Código
En un diagrama de clases, las asociaciones representan las relaciones entre las clases. Estas asociaciones pueden tener diferentes significados según el contexto del sistema que estás modelando.
El controlador se relaciona con el consultador p¿debido a que este depende de las funciones del consultador para poder funcionar. 
## Diferencia entre Composición y Agrupación
La composición implica una relación más fuerte entre objetos, donde un objeto está contenido dentro de otro objeto principal, y la existencia de la parte depende directamente del principal. En composición, si el objeto principal se destruye, también se destruyen los demás. 
Por otro lado, la agregación implica una relación menos estricta, donde un objeto puede existir de manera independiente del otro objetoprincipal al que está asociado. En agregación, la destrucción del objeto principal no necesariamente implica la destrucción de los demás.
## Qué es encapsulamiento? Qué ventajas representa? Ejemplo.
Es agrupar los atributos y métodos que operan sobre esos datos en una clase. Los detalles internos de cómo se implementa una clase están ocultos fuera de la clase y solo se accede a ellos a través de métodos públicos. Las ventajas principales serían que ocultan los detalles internos, protegen los datos y facilita el mantenimiento del código. 
Ejemplo: Tenemos una clase llamada controlador que cuenta con métodos privados que sirven para manipular el proyecto. 
## De qué manera se representa la Modularidad en POO? Ejemplo.
Esto se representa mediante la creación de clases y objetos que encapsulan datos y comportamientos relacionados, y mediante el uso de herencia, el polimorfismo y los paquetes para organizar y estructurar el código de manera clara y mantenible.

Ejemplo: Se divide la clase controlador en los metodos añadir, eliminar y borrar.

## Considera Polimorfismo.Cuál es la diferencia de usar Herencia e Interfaces? Ventajas y Desventajas.

### Herencia:
Ventajas:
Reutilizar código en clases relacionadas, tener una estructura ordenada con una clase principal y clases secundarias y añadir nuevas cosas a las clases secundarias sin cambiar la principal.

Desventajas: 
Cambios frecuentes en la clase principal, ya que afectan a las secundarias y las jerarquías son demasiado profundas y complicadas.

### Interfaces:
-Ventajas:
Desacoplar clases para que no dependan demasiado entre sí, permitir que diferentes clases compartan comportamientos comunes sin necesidad de herencia, flexibilidad, ya que una clase puede implementar varias interfaces.

-Desventajas:
Evitar la duplicación de código, ya que cada clase que implementa una interfaz debe proporcionar su propia implementación, ver de manera clara la estructura del programa, ya que no hay una jerarquía directa entre las clases.
