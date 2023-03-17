# MyStudyPlanCsharp

>1 Variables and Casting

Escribe un programa en C# que solicite al usuario ingresar dos números enteros y luego muestre el resultado de la suma, la resta, la multiplicación y la división de ambos números. Asegúrate de que el programa maneje correctamente la conversión de los valores ingresados a tipos numéricos y de que la división entre cero sea manejada adecuadamente para evitar errores.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "Calculadora".
- Declara dos variables enteras "num1" y "num2" e inicialízalas en cero.
- Solicita al usuario que ingrese los dos números y guárdalos en las variables "num1" y "num2" utilizando la función "Console.ReadLine()".
- Utiliza la función "int.TryParse()" para convertir los valores ingresados a enteros y manejar posibles errores de conversión.
- Realiza las operaciones de suma, resta, multiplicación y división de los dos números y almacena los resultados en variables separadas.
- Muestra los resultados de las operaciones utilizando la función "Console.WriteLine()" y formateando el texto de salida adecuadamente.
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>2 Operators

Escribe un programa en C# que solicite al usuario ingresar la medida de los lados de un triángulo y determine si el triángulo es equilátero, isósceles o escaleno. El programa debe mostrar el tipo de triángulo por pantalla.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "TiposDeTriangulo".
- Declara tres variables enteras "lado1", "lado2" y "lado3" e inicialízalas en cero.
- Solicita al usuario que ingrese la medida de los lados del triángulo y guárdalas en las variables correspondientes utilizando la función "Console.ReadLine()".
- Utiliza operadores de comparación y lógicos para determinar el tipo de triángulo y almacenar el resultado en una variable separada.
- Muestra el resultado utilizando la función "Console.WriteLine()" y formateando el texto de salida adecuadamente.
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>3 Conditions

Escribe un programa en C# que solicite al usuario ingresar su edad y determine si es mayor o menor de edad. Si es mayor de edad, el programa debe solicitar al usuario que ingrese su género y mostrar un mensaje apropiado. Si es menor de edad, el programa debe mostrar un mensaje indicando que no está autorizado a realizar la acción.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "MayorOMenorDeEdad".
- Declara una variable entera "edad" e inicialízala en cero.
- Solicita al usuario que ingrese su edad y guárdala en la variable "edad" utilizando la función "Console.ReadLine()".
- Utiliza una estructura condicional "if-else" para determinar si el usuario es mayor o menor de edad.
- Si el usuario es mayor de edad, solicita al usuario que ingrese su género utilizando la función "Console.ReadLine()" y muestra un mensaje apropiado utilizando la función "Console.WriteLine()".
- Si el usuario es menor de edad, muestra un mensaje indicando que no está autorizado a realizar la acción.
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>4 Loops

Escribe un programa en C# que solicite al usuario ingresar un número entero positivo y luego muestre por pantalla todos los números pares desde 0 hasta ese número (incluyendo el número ingresado).

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "NumerosPares".
- Declara una variable entera "numero" e inicialízala en cero.
- Solicita al usuario que ingrese un número entero positivo y guárdalo en la variable "numero" utilizando la función "Console.ReadLine()".
- Utiliza una estructura de bucle "for" para iterar desde cero hasta el número ingresado, de dos en dos (utilizando un incremento de 2 en el bucle).
- Dentro del bucle, utiliza una estructura condicional "if" para determinar si el número actual es par.
- Si el número es par, muestra el número por pantalla utilizando la función "Console.WriteLine()".
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>5 Arrays

Escribe un programa en C# que solicite al usuario ingresar una lista de números enteros y luego muestre por pantalla el promedio de los números ingresados.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "PromedioDeNumeros".
- Solicita al usuario que ingrese una lista de números enteros separados por comas, utilizando la función "Console.ReadLine()".
- Separa los números ingresados utilizando la función "string.Split()" y guárdalos en un array de enteros utilizando la función "Array.ConvertAll()".
- Calcula la suma de todos los números en el array utilizando un bucle "for" y una variable acumuladora.
- Calcula el promedio dividiendo la suma total por la cantidad de números en el array.
- Muestra el promedio por pantalla utilizando la función "Console.WriteLine()".
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>6 Methods

Escribe un programa en C# que solicite al usuario ingresar una lista de números enteros y luego muestre por pantalla el número más grande de la lista.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "NumeroMasGrande".
- Crea un método llamado "EncontrarMaximo" que tome como parámetro un array de números enteros y devuelva el número más grande del array.
- Dentro del método "EncontrarMaximo", utiliza un bucle "for" para iterar a través de cada elemento del array y determinar cuál es el número más grande.
- En el método "Main" del programa, solicita al usuario que ingrese una lista de números enteros separados por comas, utilizando la función "Console.ReadLine()".
- Separa los números ingresados utilizando la función "string.Split()" y guárdalos en un array de enteros utilizando la función "Array.ConvertAll()".
- Llama al método "EncontrarMaximo" pasándole el array de números ingresados como parámetro y guarda el resultado en una variable.
- Muestra el número más grande por pantalla utilizando la función "Console.WriteLine()".
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>7 Exception Handling

Escribe un programa en C# que solicite al usuario ingresar un número entero y luego muestre por pantalla el resultado de dividir 100 entre ese número. Si el usuario ingresa un número igual a cero, el programa debe mostrar un mensaje de error indicando que la división por cero no es posible.

- Crea un nuevo proyecto de consola en Visual Studio y nómbralo "DivisionPorNumero".
- En el método "Main" del programa, solicita al usuario que ingrese un número entero utilizando la función "Console.ReadLine()".
- Convierte el valor ingresado por el usuario a un número entero utilizando la función "int.Parse()".
- Crea un bloque "try" que contenga la operación de división (100 dividido por el número ingresado por el usuario).
- Dentro del bloque "try", muestra el resultado de la división utilizando la función "Console.WriteLine()".
- Si el número ingresado por el usuario es cero, se generará una excepción de división por cero. Crea un bloque "catch" para manejar esta excepción.
- Dentro del bloque "catch", muestra un mensaje de error indicando que la división por cero no es posible.
- Ejecuta el programa y asegúrate de que maneje correctamente todas las posibles entradas del usuario.

>8 Events

Crea un programa que simule una sala de cine. El programa debe permitir que los usuarios compren entradas para una película en una hora y fecha específica, y también debe permitir que se cancelen las entradas. Además, el programa debe enviar un mensaje de recordatorio por correo electrónico a los usuarios que hayan comprado entradas una hora antes de la hora de inicio de la película.

- Crea una clase "Pelicula" que contenga información sobre la película, como el título, la duración, la clasificación por edades, etc.
- Crea una clase "SalaDeCine" que tenga un arreglo de asientos disponibles y métodos para comprar entradas y cancelar entradas. Utiliza un arreglo de booleanos para representar los asientos, donde un valor "true" indica que el asiento está disponible y un valor "false" indica que el asiento ya está ocupado.
- Crea una clase "CompraDeEntrada" que contenga información sobre la compra de una entrada, como el número de asiento, el nombre del comprador, la hora y fecha de la compra, etc.
- Crea una clase "RecordatorioPorCorreoElectronico" que contenga la lógica para enviar un mensaje de correo electrónico a un usuario dado una hora antes de la hora de inicio de la película.
- En la clase "SalaDeCine", define dos eventos: "EntradaComprada" y "EntradaCancelada". Cuando se compre o se cancele una entrada, se debe invocar el evento correspondiente para notificar a cualquier objeto interesado sobre el cambio en el estado de la sala.
- En el método "Main" del programa, crea una instancia de la clase "SalaDeCine" y agrega algunos usuarios y entradas. También crea una instancia de la clase "RecordatorioPorCorreoElectronico" y suscríbete al evento "EntradaComprada" de la sala de cine para que se envíe un mensaje de recordatorio por correo electrónico cuando alguien compre una entrada.
- Ejecuta el programa y asegúrate de que se envíen los correos electrónicos de recordatorio correctamente y de que los eventos "EntradaComprada" y "EntradaCancelada" se manejen correctamente.

>9 Delegates

Crear una aplicación de consola que permita realizar operaciones matemáticas básicas (suma, resta, multiplicación y división) utilizando delegados en C#.

- Crear una clase Calculadora con los métodos Sumar, Restar, Multiplicar y Dividir, cada uno de ellos recibiendo dos números y devolviendo el resultado correspondiente.
- Crear un delegado OperacionMatematica que acepte dos números y devuelva un resultado.
- Crear una clase Program con un método Main que permita al usuario seleccionar la operación que desea realizar y los números a utilizar.
- En la clase Program, definir cuatro variables de tipo OperacionMatematica, cada una asignada a uno de los métodos de la clase Calculadora.
- Utilizar un diccionario para almacenar los nombres de las operaciones y sus respectivos delegados.
- Solicitar al usuario que seleccione una operación de la lista mostrada y que introduzca los números a utilizar.
- Utilizar el delegado correspondiente para realizar la operación matemática seleccionada.
- Mostrar el resultado al usuario.
- Ofrecer la opción de realizar otra operación o salir del programa.

>10 Classes and Objects

Crear una aplicación de consola que permita gestionar una lista de contactos utilizando clases y objetos en C#.

- Crear una clase Contacto con propiedades como nombre, apellido, correo electrónico, número de teléfono, etc.
- Crear una clase Agenda con una lista de objetos Contacto como propiedad, y métodos para añadir, eliminar y buscar contactos.
- En el método Main de la clase Program, crear una instancia de la clase Agenda y añadir algunos contactos a la lista.
- Permitir al usuario buscar contactos por nombre, apellido o correo electrónico.
- Mostrar los resultados de la búsqueda en pantalla.
- Permitir al usuario añadir, eliminar o actualizar contactos en la lista.
- Validar los datos introducidos por el usuario para asegurar que sean válidos (por ejemplo, que el correo electrónico tenga un formato correcto).
- Utilizar la serialización para guardar los contactos en un archivo y cargarlos de nuevo al iniciar la aplicación.
- Ofrecer la opción de salir del programa o guardar los cambios realizados.

>11 Data Hiding

Crear una clase CuentaBancaria que permita realizar operaciones de depósito, retirada y consulta de saldo, y aplicar el principio de ocultamiento de datos en C#.

- Crear una clase CuentaBancaria con propiedades privadas como saldo, numeroCuenta, nombreTitular, etc.
- Crear métodos públicos como Depositar, Retirar y ConsultarSaldo que permitan al usuario interactuar con la cuenta bancaria.
- Utilizar la palabra clave private para declarar las variables de instancia y public para declarar los métodos que permiten interactuar con dichas variables.
- Asegurarse de que los métodos públicos validen las operaciones de depósito y retirada para asegurarse de que el saldo de la cuenta no se vuelva negativo.
- Utilizar el modificador readonly para evitar que las propiedades de la clase CuentaBancaria sean modificadas fuera de la propia clase.
- Crear una clase Cliente que tenga una lista de cuentas bancarias y permita realizar operaciones como agregar o eliminar cuentas, consultar saldos de todas las cuentas, etc.
- Utilizar la clase CuentaBancaria en conjunto con la clase Cliente para permitir al usuario interactuar con las cuentas bancarias de forma segura y controlada.

>12 Composition, Aggregate and Association

Library Management System

- Crear una clase Book con propiedades como Title, Author, ISBN, PublicationDate, Genre, etc.
- Crear una clase Library que contenga una lista de objetos Book.
- Implementar una relación de composición entre la clase Library y Book, donde una instancia de Library contenga una lista de instancias de Book.
- Implementar métodos para agregar, eliminar y buscar libros en la biblioteca.
- Implementar una clase Member con propiedades como Name, Address, PhoneNumber, etc.
- Crear una clase Membership que contenga una lista de objetos Member.
- Implementar una relación de agregación entre la clase Library y Membership, donde una instancia de Library contenga una lista de instancias de Membership.
- Implementar métodos para agregar y eliminar miembros en la biblioteca.
- Implementar una clase Borrow con propiedades como BorrowDate, ReturnDate, Fine, etc.
- Crear una clase BorrowHistory que contenga una lista de objetos Borrow.
- Implementar una relación de asociación entre las clases Book y Member a través de la clase Borrow, donde una instancia de Book puede ser prestada por un miembro y una instancia de Member puede tomar prestados varios libros.
- Implementar métodos para prestar y devolver libros, y para generar el historial de préstamos y multas.
- Agregar excepciones y manejo de errores en caso de que los libros no estén disponibles o los miembros tengan multas pendientes.
- Crear una interfaz de usuario para interactuar con la biblioteca, donde los usuarios puedan agregar, buscar y prestar libros, agregar y eliminar miembros, etc.

>13 Inheritance

Banking System

- Crea una clase base llamada "CuentaBancaria" que contenga los campos básicos de una cuenta bancaria, como el número de cuenta, el saldo y el titular de la cuenta.
- Crea una clase llamada "CuentaCorriente" que herede de la clase "CuentaBancaria" y que incluya campos adicionales como una tasa de interés y un límite de crédito.
- Crea una clase llamada "CuentaDeAhorro" que también herede de "CuentaBancaria" y que incluya un campo adicional para la tasa de interés.
- Implementa métodos en las clases "CuentaCorriente" y "CuentaDeAhorro" que permitan hacer depósitos y retiros.
- Implementa un método en la clase "CuentaBancaria" que permita imprimir el saldo actual de la cuenta.
- Crea una clase llamada "Cliente" que contenga un campo para el nombre del cliente y un array de objetos "CuentaBancaria" que representen las cuentas que tiene el cliente.
- Implementa métodos en la clase "Cliente" que permitan agregar y eliminar cuentas bancarias de un cliente.
- Prueba el funcionamiento del sistema creando algunos clientes y realizando operaciones de depósito y retiro en sus cuentas bancarias.

>14 Polymorphism

Crear una calculadora que pueda realizar operaciones aritméticas básicas (+, -, *, /) con diferentes tipos de datos.

- Crear una clase abstracta llamada Operacion que tenga como propiedad dos números (operandos) y un método abstracto llamado Calcular() que devuelva el resultado de la operación.
- Crear cuatro clases que hereden de la clase Operacion, cada una para una operación aritmética básica (suma, resta, multiplicación, división).
- Implementar el método Calcular() en cada una de las subclases, realizando la operación correspondiente.
- Crear una clase Calculadora que tenga un método EstablecerOperacion() que reciba como parámetro una Operacion y establezca los operandos de la operación.
- Crear un método Calcular() en la clase Calculadora que invoque el método Calcular() de la operación establecida anteriormente y devuelva el resultado.
- En la función principal, crear una instancia de la clase Calculadora y llamar al método EstablecerOperacion() con una instancia de alguna de las subclases de Operacion (por ejemplo, Suma) y establecer los operandos de la operación.
- Llamar al método Calcular() de la calculadora y mostrar el resultado por pantalla.

>15 Abstract Classes and Interfaces

Creación de una calculadora básica utilizando clases abstractas e interfaces.

- Crear una interfaz "ICalculator" con los métodos "Add", "Subtract", "Multiply" y "Divide".
- Crear una clase abstracta "BasicCalculator" que implemente la interfaz "ICalculator".
- Agregar los métodos abstractos "Add" y "Subtract" a la clase "BasicCalculator".
- Crear una clase "ScientificCalculator" que extienda "BasicCalculator" y agregue los métodos "Multiply" y "Divide".
- Implementar los métodos abstractos "Add" y "Subtract" en la clase "BasicCalculator" y los métodos "Multiply" y "Divide" en la clase "ScientificCalculator".
- Crear una instancia de la clase "BasicCalculator" y una instancia de la clase "ScientificCalculator".
- Probar los métodos de ambas instancias para verificar que la calculadora básica y la calculadora científica funcionen correctamente.

>16 System.Random

Juego de adivinanza de números

- Generar un número aleatorio usando System.Random.
- Pedir al usuario que adivine el número generado.
- Comprobar si el número adivinado es igual al número generado.
- Si el número adivinado es igual al número generado, mostrar un mensaje de felicitación.
- Si el número adivinado es menor que el número generado, mostrar un mensaje que indique que el número adivinado es menor y pedir al usuario que vuelva a intentarlo.
- Si el número adivinado es mayor que el número generado, mostrar un mensaje que indique que el número adivinado es mayor y pedir al usuario que vuelva a intentarlo.
- Repetir los pasos 2-6 hasta que el usuario adivine el número generado o hasta que se alcance un número máximo de intentos.

>17 Garbage Collector

Simulación de un programa de gestión de memoria

- Crear una clase MemoryBlock que tenga una propiedad Size que represente el tamaño del bloque de memoria, y un método Dispose que libere el bloque de memoria.
- Crear una clase MemoryManager que tenga un método Allocate que reciba como parámetro el tamaño del bloque de memoria a asignar y retorne un objeto de tipo MemoryBlock con el tamaño especificado. Esta clase debe llevar un control de los bloques de memoria asignados y liberados.
- Crear una aplicación de consola que instancie un objeto de tipo MemoryManager y permita al usuario solicitar la asignación de bloques de memoria de diferentes tamaños. Al liberar un bloque de memoria, la aplicación debe llamar al método Dispose del objeto MemoryBlock.
- Añadir la funcionalidad de monitoreo del consumo de memoria de la aplicación, utilizando la clase GC de C# para obtener información sobre la cantidad de memoria asignada y liberada por el programa.

>18 Asynchronous Programming

Simple Asynchronous Task

- Crea un proyecto de consola en C#.
- Define una función Task<int> CountNumbersAsync(int n) que reciba un número entero n como argumento. Esta función debe devolver una tarea que cuente desde 1 hasta n en un hilo diferente al hilo principal.
- Crea una función async llamada TestAsync que invoque CountNumbersAsync y espere a que se complete la tarea.
- Dentro de TestAsync, después de esperar a que se complete la tarea, imprime el resultado en la consola.
- Crea una función Main que invoque TestAsync y espere a que se complete la tarea.

>19 Tasks and Parallelism

Parallel Image Processing

- Selecciona un conjunto de imágenes para procesar.
- Crea una lista de tareas (Task) para procesar cada imagen en paralelo utilizando el método Parallel.ForEach().
- Dentro de cada tarea, utiliza la librería System.Drawing para cargar la imagen, aplicar una operación (por ejemplo, escala de grises o aumento de contraste), y guardar la imagen procesada en un nuevo archivo.
- Cuando todas las tareas se completen, muestra un mensaje indicando que el procesamiento ha terminado y muestra las imágenes procesadas.

>20 Common LINQ Methods

Crear una aplicación de consola que utilice Common LINQ Methods para manipular una lista de objetos.

- Crea una clase llamada "Persona" con las siguientes propiedades: Nombre (string), Edad (int) y Profesión (string).
- Crea una lista de objetos de tipo Persona y agrega al menos 5 personas a la lista.
- Utiliza el método "Where" para filtrar las personas cuya edad sea mayor a 30 y almacénalas en una nueva lista.
- Utiliza el método "OrderBy" para ordenar la lista de personas por edad de forma ascendente.
- Utiliza el método "Select" para proyectar la lista de personas en una lista de strings que contenga solo los nombres de las personas.
- Utiliza el método "Any" para verificar si hay alguna persona en la lista que tenga la profesión de "Abogado".
- Utiliza el método "All" para verificar si todas las personas en la lista tienen una edad mayor a 20.
- Utiliza el método "First" para obtener la primera persona en la lista y mostrar su nombre y profesión en la consola.
- Utiliza el método "Count" para contar cuántas personas en la lista tienen una edad mayor a 25.
- Muestra los resultados de cada operación en la consola para verificar que se hayan realizado correctamente.

>21 Advanced LINQ Expressions

Crear una aplicación de consola que utilice Advanced LINQ Expressions para manipular una lista de objetos.

- Crea una clase llamada "Producto" con las siguientes propiedades: Nombre (string), Precio (decimal), FechaDeVencimiento (DateTime) y Categoría (string).
- Crea una lista de objetos de tipo Producto y agrega al menos 10 productos a la lista.
- Utiliza el método "GroupBy" para agrupar los productos por categoría y obtener el total de productos en cada categoría.
- Utiliza el método "Join" para unir la lista de productos con una lista de categorías y obtener una lista de productos con sus respectivas categorías.
- Utiliza el método "Any" con una expresión lambda para verificar si hay algún producto en la lista que tenga un precio mayor a $100.
- Utiliza el método "All" con una expresión lambda para verificar si todos los productos en la lista tienen una fecha de vencimiento posterior a la fecha actual.
- Utiliza el método "Max" para obtener el producto con el precio más alto en la lista y mostrar su nombre y precio en la consola.
- Utiliza el método "Where" con una expresión lambda para filtrar los productos que vencen en los próximos 30 días y mostrar sus nombres y fechas de vencimiento en la consola.
- Utiliza el método "Average" para obtener el precio promedio de los productos en la lista y mostrarlo en la consola.
- Muestra los resultados de cada operación en la consola para verificar que se hayan realizado correctamente.

>22 Linked List

Crear una aplicación de consola que implemente una Linked List para almacenar y manipular una lista de números enteros.

- Crea una clase llamada "Nodo" con las siguientes propiedades: Valor (int) y Siguiente (Nodo).
- Crea una clase llamada "LinkedList" con los siguientes métodos:
"AgregarAlFinal": agrega un nodo con el valor especificado al final de la lista.
"Eliminar": elimina el nodo con el valor especificado de la lista.
"Mostrar": muestra los valores de todos los nodos en la lista en la consola.
- Crea una instancia de la clase LinkedList y agrega al menos 5 números enteros a la lista utilizando el método "AgregarAlFinal".
- Muestra los valores de los nodos en la lista utilizando el método "Mostrar".
- Elimina el nodo con el valor igual a 3 de la lista utilizando el método "Eliminar".
- Muestra los valores de los nodos en la lista actualizada utilizando el método "Mostrar".
- Agrega un nuevo nodo con el valor igual a 10 al final de la lista utilizando el método "AgregarAlFinal".
- Muestra los valores de los nodos en la lista actualizada utilizando el método "Mostrar".
- Implementa un método llamado "Buscar" que reciba como parámetro un valor entero y devuelva el nodo con ese valor, si existe en la lista.
- Utiliza el método "Buscar" para buscar el nodo con el valor igual a 5 y mostrar su valor en la consola.

>23 Stacks and Queues

Crear una aplicación de consola que utilice stacks y queues para manipular una lista de nombres.

- Crea una lista de nombres de personas y agrégales al menos 5 nombres.
- Crea un stack y agrega los nombres de la lista en el mismo orden en que se encuentran en la lista.
- Crea un queue y agrega los nombres de la lista en orden inverso al que se encuentran en la lista.
- Utiliza el método "Peek" del stack para mostrar el nombre en la cima del stack en la consola.
- Utiliza el método "Dequeue" del queue para mostrar el primer nombre en la cola en la consola.
- Utiliza el método "Push" del stack para agregar un nuevo nombre a la lista en la posición superior del stack.
- Utiliza el método "Enqueue" del queue para agregar un nuevo nombre a la lista en la última posición de la cola.
- Muestra los valores del stack y del queue en la consola para verificar que se hayan agregado correctamente los nuevos nombres.
- Utiliza el método "Pop" del stack para eliminar el último nombre agregado de la lista.
- Utiliza el método "Dequeue" del queue para eliminar el primer nombre agregado de la lista.
- Muestra los valores actualizados del stack y del queue en la consola para verificar que se hayan eliminado correctamente los nombres.

>24 Hashing

Crear una aplicación de consola que implemente una tabla de hashing para almacenar y manipular una lista de productos.

- Crea una clase "Producto" con las siguientes propiedades: Nombre (string), Código (int), Precio (decimal).
- Crea una clase "HashTable" con los siguientes métodos:
"AgregarProducto": agrega un producto a la tabla de hashing utilizando su código como clave.
"EliminarProducto": elimina un producto de la tabla de hashing utilizando su código como clave.
"BuscarProducto": busca un producto en la tabla de hashing utilizando su código como clave y devuelve el producto encontrado.
- Crea una instancia de la clase HashTable.
- Agrega al menos 5 productos a la tabla de hashing utilizando el método "AgregarProducto".
- Busca un producto en la tabla de hashing utilizando el método "BuscarProducto" y muestra sus propiedades en la consola.
- Elimina un producto de la tabla de hashing utilizando el método "EliminarProducto".
- Muestra todos los productos en la tabla de hashing utilizando un bucle for y mostrando sus propiedades en la consola.
- Agrega un nuevo producto a la tabla de hashing utilizando el método "AgregarProducto".
- Muestra todos los productos en la tabla de hashing utilizando un bucle foreach y mostrando sus propiedades en la consola.
- Modifica el código de un producto existente en la tabla de hashing y muestra sus propiedades actualizadas en la consola.

>25 Graph

Crear una aplicación de consola que implemente un grafo dirigido para representar y manipular una red de carreteras.

- Crea una clase "Carretera" con las siguientes propiedades: Origen (string), Destino (string), Distancia (double).
- Crea una clase "GrafoDirigido" con los siguientes métodos:
"AgregarVertice": agrega un vértice (una ciudad) al grafo.
"AgregarArista": agrega una arista (una carretera) al grafo, especificando su origen, destino y distancia.
"EliminarVertice": elimina un vértice (una ciudad) del grafo y todas las aristas que lo conectan con otros vértices.
"EliminarArista": elimina una arista (una carretera) del grafo, especificando su origen y destino.
"ObtenerVecinos": devuelve una lista de los vértices adyacentes (ciudades conectadas por carreteras) a un vértice específico.
- Crea una instancia de la clase GrafoDirigido.
- Agrega al menos 5 ciudades al grafo utilizando el método "AgregarVertice".
- Agrega al menos 7 carreteras al grafo utilizando el método "AgregarArista".
- Muestra en la consola la lista de adyacencia del grafo para cada ciudad utilizando el método "ObtenerVecinos".
- Elimina una ciudad del grafo utilizando el método "EliminarVertice".
- Elimina una carretera del grafo utilizando el método "EliminarArista".
- Muestra en la consola la lista de adyacencia del grafo actualizada para cada ciudad utilizando el método "ObtenerVecinos".
- Utiliza el algoritmo de Dijkstra para encontrar el camino más corto entre dos ciudades del grafo. Muestra el camino y la distancia total en la consola.

>26 Binary Tree

Crear una aplicación de consola que implemente un árbol binario de búsqueda y permita realizar operaciones de búsqueda, inserción y eliminación de nodos.

- Crea una clase "Nodo" con las siguientes propiedades: Valor (int), NodoIzquierdo (Nodo) y NodoDerecho (Nodo).
- Crea una clase "ArbolBinarioBusqueda" con los siguientes métodos:
"Insertar": inserta un nuevo nodo en el árbol, verificando que se mantenga la propiedad de árbol binario de búsqueda.
"Buscar": busca un nodo con un valor específico en el árbol y devuelve el nodo encontrado (o null si no se encuentra).
"Eliminar": elimina un nodo con un valor específico del árbol, verificando que se mantenga la propiedad de árbol binario de búsqueda.
"RecorridoPreOrden": realiza un recorrido preorden del árbol (nodo actual, nodo izquierdo, nodo derecho).
"RecorridoInOrden": realiza un recorrido inorden del árbol (nodo izquierdo, nodo actual, nodo derecho).
"RecorridoPostOrden": realiza un recorrido postorden del árbol (nodo izquierdo, nodo derecho, nodo actual).
- Crea una instancia de la clase ArbolBinarioBusqueda.
- Inserta al menos 7 nodos en el árbol utilizando el método "Insertar".
- Realiza un recorrido preorden del árbol utilizando el método "RecorridoPreOrden" y muestra el resultado en la consola.
- Realiza un recorrido inorden del árbol utilizando el método "RecorridoInOrden" y muestra el resultado en la consola.
- Realiza un recorrido postorden del árbol utilizando el método "RecorridoPostOrden" y muestra el resultado en la consola.
- Busca un nodo con un valor específico utilizando el método "Buscar" y muestra el resultado en la consola.
- Elimina un nodo con un valor específico utilizando el método "Eliminar".
- Realiza un recorrido inorden del árbol actualizado utilizando el método "RecorridoInOrden" y muestra el resultado en la consola.

>27 Trie

Implementar un Trie en C# para almacenar y buscar palabras en un diccionario.

- Definir la estructura de nodo para el Trie que incluya una propiedad para la letra, una propiedad para indicar si es una palabra completa, y una lista de hijos.
- Crear una clase para el Trie que tenga un nodo raíz y los métodos necesarios para insertar y buscar palabras en el Trie.
- Implementar el método para insertar palabras en el Trie. Para ello, se debe recorrer la palabra letra por letra, creando nuevos nodos si es necesario, y establecer la propiedad de palabra completa en el último nodo.
- Implementar el método para buscar palabras en el Trie. Se debe recorrer el Trie letra por letra y verificar si cada nodo tiene un hijo que coincida con la siguiente letra de la palabra buscada. Si se llega a un nodo que indica que es una palabra completa, se ha encontrado la palabra buscada.
- Probar la implementación con un diccionario de palabras y verificar que las palabras se puedan insertar y buscar correctamente en el Trie.

>28 Heap

Implementar un Heap (montículo) en C# para ordenar un arreglo de números.

- Definir la estructura de Heap que incluya un arreglo de elementos y un contador para el número de elementos en el Heap.
- Crear una clase para el Heap que tenga los métodos necesarios para insertar elementos, eliminar el elemento de mayor prioridad y ordenar el arreglo.
- Implementar el método para insertar elementos en el Heap. Para ello, se debe agregar el nuevo elemento al final del arreglo y luego hacer un recorrido hacia arriba intercambiando el elemento con su padre mientras el padre tenga una prioridad menor que el elemento.
- Implementar el método para eliminar el elemento de mayor prioridad. Este es el elemento en la posición 0 del arreglo. Se debe reemplazar este elemento con el último elemento del arreglo y hacer un recorrido hacia abajo intercambiando el elemento con su hijo de mayor prioridad mientras el hijo tenga una prioridad mayor que el elemento.
- Implementar el método para ordenar el arreglo utilizando el Heap. Para ello, se debe insertar todos los elementos del arreglo en el Heap y luego eliminar el elemento de mayor prioridad y agregarlo al final del arreglo ordenado. Este proceso se repite hasta que se hayan eliminado todos los elementos del Heap.
- Probar la implementación con un arreglo de números y verificar que se ordene correctamente utilizando el Heap.

>29 Funtional Programming

Implementar una función en C# que reciba una lista de números enteros y devuelva una nueva lista con los números pares elevados al cuadrado.

- Definir la función en C# utilizando programación funcional. La función debe recibir una lista de números enteros y devolver una nueva lista con los números pares elevados al cuadrado.
- Utilizar la función de mapeo (map) para aplicar una función a cada elemento de la lista de entrada. En este caso, se debe aplicar una función que eleve al cuadrado los números pares y devuelva el número original para los números impares.
- Utilizar la función de filtrado (filter) para obtener una lista que solo contenga los números pares de la lista original.
- Combinar las funciones de mapeo y filtrado utilizando la función de reducción (reduce) para obtener la lista final con los números pares elevados al cuadrado.
- Probar la implementación con una lista de números y verificar que se devuelva una nueva lista con los números pares elevados al cuadrado.

>30 AOP (Aspect Oriented Programming)

Implementar el registro de tiempo de ejecución de métodos utilizando AOP en C#.

- Definir un atributo personalizado en C# que se utilizará para marcar los métodos a los que se desea agregar el registro de tiempo de ejecución.
- Utilizar la biblioteca PostSharp, que es una biblioteca de AOP para .NET, para crear un aspecto personalizado que se encargará de medir el tiempo de ejecución del método y escribirlo en un archivo de registro.
- Aplicar el atributo personalizado a los métodos que se desean registrar y utilizar el aspecto personalizado para realizar el registro de tiempo de ejecución.
- Configurar el aspecto personalizado para que escriba la información de registro en un archivo de registro.
- Probar la implementación con algunos métodos y verificar que el tiempo de ejecución se registre correctamente en el archivo de registro.

>31 Real Time Programming and Notification Events

Implementar un sistema de notificación de eventos en tiempo real utilizando C# y SignalR.

- Definir la estructura de datos para el evento que se va a notificar en tiempo real. Por ejemplo, un objeto que contenga el nombre del evento, la fecha y hora en que ocurrió y cualquier otra información relevante.
- Crear una clase en C# que se encargue de generar los eventos y almacenarlos en una lista.
- Configurar un hub de SignalR en C# para enviar los eventos en tiempo real a los clientes conectados.
- Configurar un cliente de SignalR en C# para recibir los eventos en tiempo real y mostrarlos en la pantalla.
- Probar la implementación simulando la generación de eventos y verificar que los eventos se envíen en tiempo real a los clientes conectados y se muestren en la pantalla.

>32 Patterns

Implementar un sistema de venta de productos en línea que utilice los patrones de diseño MVC, Factory, Singleton, Observer, Strategy, Adapter, Decorator, Command, Template Method, Iterator, Visitor, Composite, Facade, Bridge y Chain of Responsibility.

- Crear la estructura del proyecto utilizando el patrón de diseño MVC (Modelo Vista Controlador), donde el modelo representa los datos de los productos y la lógica de negocio, la vista representa la interfaz de usuario y el controlador actúa como intermediario entre el modelo y la vista.
- Utilizar el patrón de diseño Factory para crear instancias de los diferentes tipos de productos que se pueden vender, como productos físicos y productos digitales. La clase Factory podría tener un método CreateProduct que acepte un parámetro que indique el tipo de producto que se desea crear y devolver una instancia de la clase correspondiente.
- Utilizar el patrón de diseño Singleton para garantizar que solo haya una instancia de la clase Factory en todo el sistema.
- Utilizar el patrón de diseño Observer para notificar a los usuarios cuando se agreguen nuevos productos o se realicen cambios en los productos existentes.
- Utilizar el patrón de diseño Strategy para permitir que los usuarios elijan diferentes opciones de envío y de pago para sus pedidos.
- Utilizar el patrón de diseño Adapter para integrar sistemas de pago de terceros en el sistema de venta de productos.
- Define las clases de productos que se pueden vender, como "Producto", "ProductoDigital", "ProductoFísico", "ProductoDescargable", etc. Implementa el patrón de diseño Decorator para agregar funcionalidades adicionales a los productos, como la opción de envío físico o la descarga digital.
- Implementa el patrón de diseño Command para crear un sistema de órdenes de compra. Crea una clase "OrderCommand" que tenga un método "Execute" que maneje el proceso de compra, y utiliza esta clase para crear diferentes tipos de órdenes de compra, como "OrderCommandFisico", "OrderCommandDigital", etc.
- Usa el patrón de diseño Template Method para implementar el proceso de compra de manera consistente para todos los tipos de órdenes. Crea una clase abstracta "PurchaseProcessTemplate" que tenga un método común "Purchase" y define las operaciones específicas para cada tipo de orden de compra en clases que extiendan esta clase base.
- Implementa el patrón de diseño Iterator para recorrer y acceder a los productos disponibles en el sistema de venta. Crea una clase "ProductIterator" que implemente la interfaz "IIterator" y tenga un método "Next" que devuelva el siguiente elemento disponible.
- Usa el patrón de diseño Visitor para realizar diferentes operaciones en los productos. Crea una interfaz "IProductVisitor" con métodos para visitar cada tipo de producto y luego implementa esta interfaz en una clase que realice diferentes operaciones sobre los productos, como "ProductPrintVisitor" para imprimir los detalles del producto.
- Implementa el patrón de diseño Composite para organizar los diferentes tipos de productos en una estructura de árbol. Crea una clase "ProductComposite" que tenga una lista de productos y agrega productos individuales o productos compuestos a esta lista. Utiliza esta estructura de árbol para realizar diferentes operaciones en los productos de manera recursiva.
- Usa el patrón de diseño Facade para simplificar el acceso a los diferentes componentes del sistema de venta. Crea una clase "VentaFacade" que tenga métodos para realizar operaciones comunes, como agregar productos al carrito de compras o realizar una compra, que llamen a los diferentes componentes del sistema de venta.
- Implementa el patrón de diseño Bridge para separar la interfaz de usuario de la implementación del sistema de venta. Crea una interfaz gráfica de usuario (GUI) para el sistema de venta y separa la lógica de negocios de la interfaz gráfica de usuario utilizando una clase "VentaBridge" que actúe como intermediario.
- Usa el patrón de diseño Chain of Responsibility para manejar las diferentes excepciones y errores que puedan surgir durante el proceso de compra. Crea una cadena de manejadores de excepciones, como "ShippingExceptionHandler" o "PaymentExceptionHandler", y utiliza esta cadena para manejar diferentes tipos de excepciones de manera ordenada.

>33 Unit Testing

Desarrollar una calculadora básica en C# utilizando el enfoque TDD (Desarrollo guiado por pruebas) para implementar pruebas unitarias y asegurar la calidad del código.

- Definir los requerimientos de la calculadora, como por ejemplo, las operaciones que debe permitir y los tipos de datos que debe aceptar.
- Escribir una prueba unitaria para validar la funcionalidad de la operación de suma. Esta prueba debe asegurarse de que la calculadora sume correctamente dos números.
- Ejecutar la prueba unitaria y asegurarse de que falle, ya que aún no se ha implementado la funcionalidad.
- Implementar la operación de suma en la calculadora.
- Ejecutar nuevamente la prueba unitaria y asegurarse de que ahora pase.
- Repetir los pasos 2 a 5 para todas las operaciones que se hayan definido en los requerimientos.
- Escribir pruebas unitarias adicionales para validar situaciones especiales, como por ejemplo, la división entre cero o el ingreso de datos no válidos.
- Ejecutar todas las pruebas unitarias y asegurarse de que todas pasen.
- Refactorizar el código de la calculadora para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Ejecutar nuevamente todas las pruebas unitarias y asegurarse de que siguen pasando.

>34 Communication and Data Manipulation through WebServices, RESTful, APIs, etc

Desarrollar una aplicación de consola en C# que consuma la API pública de una red social, como por ejemplo, Twitter o Instagram, y realice algunas operaciones de manipulación de datos, como por ejemplo, obtener los últimos tweets o publicaciones y analizar el sentimiento de los mismos.

- Obtener las credenciales de la API pública de la red social que se va a utilizar.
- Crear un proyecto de consola en C# y agregar las dependencias necesarias para consumir la API.
- Escribir el código para realizar la autenticación con la API utilizando las credenciales obtenidas en el paso 1.
- Escribir el código para consumir la API y obtener los últimos tweets o publicaciones de la red social.
- Escribir el código para analizar el sentimiento de los tweets o publicaciones utilizando una biblioteca de análisis de sentimiento, como por ejemplo, NLTK (Natural Language Toolkit) o TextBlob.
- Imprimir los resultados del análisis de sentimiento en la consola.
- Refactorizar el código para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Agregar manejo de errores en el código para asegurarse de que la aplicación sea robusta y maneje situaciones inesperadas.
- Ejecutar la aplicación de consola y asegurarse de que funciona correctamente.
- Si se desea, se puede agregar una funcionalidad adicional, como por ejemplo, permitir al usuario ingresar un hashtag o término de búsqueda para obtener los tweets o publicaciones relacionados con ese término.

>35 CLR

Desarrollar una aplicación en C# que muestre cómo interactúa el Common Language Runtime (CLR) con el código C# y cómo se gestionan los recursos de la aplicación.

- Crear un proyecto de consola en C# y escribir el código para imprimir algunos mensajes en la consola.
- Ejecutar el programa y observar cómo se compila el código C# en código intermedio (CIL) y cómo se ejecuta en el CLR.
- Escribir el código para crear un objeto y llamar a un método de ese objeto.
- Observar cómo el CLR gestiona la memoria y cómo se elimina el objeto cuando ya no es necesario.
- Escribir el código para crear un objeto que implemente la interfaz IDisposable y utilice un recurso no administrado, como por ejemplo, un archivo.
- Implementar el método Dispose para liberar el recurso no administrado y observar cómo el CLR gestiona la eliminación del objeto.
- Escribir el código para crear un objeto que genere una excepción y observar cómo el CLR gestiona la excepción y cómo se limpian los recursos.
- Refactorizar el código para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Agregar manejo de errores en el código para asegurarse de que la aplicación sea robusta y maneje situaciones inesperadas.
- Ejecutar la aplicación y observar cómo el CLR gestiona los recursos y cómo se manejan las excepciones.

>36 COM+

Desarrollar una aplicación en C# que utilice COM+ para implementar transacciones distribuidas y asegurar la integridad de los datos en caso de fallas en la red.

- Crear una base de datos en SQL Server y crear una tabla para almacenar información.
- Crear un proyecto de biblioteca de clases en C# y agregar referencias a las bibliotecas necesarias para utilizar COM+.
- Escribir el código para crear un componente COM+ que se conecte a la base de datos y permita leer y escribir datos en la tabla.
- Escribir el código para definir una transacción distribuida y asegurarse de que el componente COM+ pueda participar en la transacción.
- Escribir el código para utilizar el componente COM+ y realizar algunas operaciones de lectura y escritura de datos.
- Simular una falla en la red y observar cómo se comporta la transacción distribuida y cómo se asegura la integridad de los datos.
- Refactorizar el código para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Agregar manejo de errores en el código para asegurarse de que la aplicación sea robusta y maneje situaciones inesperadas.
- Ejecutar la aplicación y asegurarse de que funciona correctamente y que los datos se mantienen íntegros en caso de fallas en la red.
- Si se desea, se puede agregar una funcionalidad adicional, como por ejemplo, permitir al usuario ingresar datos en la consola y escribirlos en la tabla de la base de datos utilizando la transacción distribuida.

>37 Entity Framework

Desarrollar una aplicación en C# que utilice Entity Framework para interactuar con una base de datos y realizar operaciones de lectura, escritura y actualización de datos.

- Crear una base de datos en SQL Server y agregar algunas tablas con datos de ejemplo.
- Crear un proyecto de consola en C# y agregar las referencias necesarias para utilizar Entity Framework.
- Configurar Entity Framework para conectarse a la base de datos y generar el modelo de objetos que represente las tablas y sus relaciones.
- Escribir el código para consultar datos de la base de datos y mostrarlos en la consola.
- Escribir el código para insertar nuevos datos en la base de datos y mostrarlos en la consola.
- Escribir el código para actualizar datos existentes en la base de datos y mostrarlos en la consola.
- Escribir el código para eliminar datos de la base de datos y mostrar los datos actualizados en la consola.
- Refactorizar el código para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Agregar manejo de errores en el código para asegurarse de que la aplicación sea robusta y maneje situaciones inesperadas.
- Ejecutar la aplicación y asegurarse de que funciona correctamente y que los datos se mantienen íntegros en la base de datos. Si se desea, se puede agregar una funcionalidad adicional, como por ejemplo, permitir al usuario ingresar datos en la consola y escribirlos en la base de datos utilizando Entity Framework.

>38 GraphQL

Desarrollar una aplicación en C# que utilice GraphQL para implementar una API que permita realizar consultas y mutaciones sobre una base de datos.

- Crear una base de datos en SQL Server y agregar algunas tablas con datos de ejemplo.
- Configurar la aplicación para utilizar GraphQL y definir los tipos de datos y esquemas que se utilizarán para la API.
- Escribir el código para definir los resolvers, que son los encargados de recibir las consultas y mutaciones de GraphQL y realizar las operaciones correspondientes en la base de datos.
- Escribir el código para realizar consultas sencillas, como por ejemplo, obtener todos los registros de una tabla o filtrar los registros según algunos criterios.
- Escribir el código para realizar mutaciones sencillas, como por ejemplo, insertar un nuevo registro en una tabla o actualizar un registro existente.
- Escribir el código para implementar consultas y mutaciones más complejas, como por ejemplo, realizar búsquedas por campos anidados, aplicar filtros avanzados, realizar paginación y ordenamiento de resultados, entre otros.
- Refactorizar el código para asegurarse de que es legible, mantenible y cumple con los estándares de calidad.
- Agregar manejo de errores en el código para asegurarse de que la aplicación sea robusta y maneje situaciones inesperadas.
- Ejecutar la aplicación y asegurarse de que funciona correctamente y que las consultas y mutaciones se realizan correctamente en la base de datos.
- Si se desea, se puede agregar una funcionalidad adicional, como por ejemplo, autenticación y autorización de usuarios, integración con otras APIs, entre otras.