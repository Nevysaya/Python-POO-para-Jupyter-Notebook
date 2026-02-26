# Python-POO-para-Jupyter-Notebook
La Programación Orientada a Objetos (POO) es un paradigma de programación que organiza el diseño de software en torno a datos u “objetos”, en lugar de funciones y lógica. Es básicamente, una forma de programar que intenta imitar cómo vemos el mundo real.
En POO existen: La Clase, que es el diseño, plano o molde. Por ejemplo: Tienes el plan de una casa en la computadora, no puedes entrar a la casa y abrir las puertas. Es sólo un dibujo y El Objeto (también llamado Instancia), es lo que sale del plano; vendría siendo la casa real, de ladrillos, con puertas de madera y techo de platabanda.
En POO, en lugar de tener un código lineal que se lee de arriba abajo, creamos “moldes” que contienen tanto la información como las acciones que se pueden realizar con ella.
Para que un lenguaje sea considerado a objetos, debe cumplir con estos cuatro conceptos o pilares fundamentales:
•	Abstracción
Es el proceso de simplificar la realidad. Al crear un objeto, sólo nos enfocamos en las características que importan para nuestro programa. En otras palabras, es analizar qué Atributos (Datos) y Métodos (funcionalidad) va a tener la aplicación para llevarla a una clase. Por ejemplo: Si diseñas un sistema para un taller mecánico, te interesaría el motor y el kilometraje del carro, pero no el color de las alfombras.

•	Encapsulamiento
Consiste en ocultar los detales internos de cómo funciona un objeto y proteger su estado. Es una protección de manipulaciones No Autorizadas. En Python, esto se logra mediante el uso de guiones bajos (_ ó __) para indicar qué atributo es privado. Ejemplo: Usas el volante y los pedales, pero no necesitas manipular directamente en el motor para que el carro arranque.

•	Herencia
Permite crear clases nuevas a partir de clases existentes. La clase hija “hereda” la clase padre, pero puede añadir las sus propias. Es decir, cuando una clase hereda atributos y métodos y se adicionan otros. Ejemplo: Una clase Vehículo puede ser el padre de carro y camión. Ambos tienen ruedas pero el camión tiene capacidad de carga.

•	Poliformismo
Es la capacidad que tienen diferentes objetos de responder de manera distinta al mismo mensaje (o método). Ejemplo: si tienes una lista de animales (objetos) y a todos les das el mismo comando (orden) de hacer_sonido(), el resultado va a variar, según el objeto.
Para plasmar un programa y verlo funcionar una de las opciones más rápidas es Google Colab (online). No necesita ser instalada. Es un Jupyter Notebook en la nube. Sólo se necesita una cuenta Gmail.
Entrando a colab.research.google.com, le damos click en “Nuevo Cuaderno”, se pega el código de la clase en una celda y se presiona el botón Play.
También se puede usar con Visual Studio Code, que permite tener los archivos de código (.py) y los cuadernos de notas (.ipynb) en un solo lugar.
