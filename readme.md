FUNDAMENTOS DE PROGRAMACION



RETO 1:

El algoritmo desarrollado por el equipo de tecnología. “Caso TuTienda”

TuTienda es una empresa de e-commerce que ofrece más de 1000 productos en su catálogo online, actualmente cuenta con 10 mil usuarios activos y a realizado más de 150 mil pedidos en los últimos 3 meses, cuentan con servicio de envió por moto que actualmente están evaluando si continuar con el servicio de envío o adquirir un proveedor que les brinde el servicio ya que los costos de mantener todo el servicio de envío son muy altos.
TuTienda ofrece actualmente tarifas muy altas de envío y lo que suelen hacer sus clientes es comprar con recojo en tienda o pedir servicios como Glovo donde hay una persona que compra y envía el producto donde estas.

PROBLEMA:

Los ejecutivos de TuTienda descubrieron que el servicio de envío no está funcionando puesto que solo hubo 10% de los pedidos con envíos a domicilio frente a 90 % de pedidos con recojo en tienda.
Se quería ver la manera de poder ajustar los costos de envío y replantear las variables que están detrás del costo y hubo diferentes ideas de parte de los analistas de costos
Por otro lado, el equipo de tecnología que había desarrollado toda la plataforma tenía algunas ideas de cómo poder mejorar el costo del envío agregando la variable de tiempo y distancia de los puntos de entrega.
El gerente de operaciones tenía un contacto de una empresa que brinda servicios de envíos ofreciendo una tarifa cómoda en comparación de los gastos que incurre tener una flota de motorizados propios.

PREGUNTAS:

1. ¿Cuál es la importancia de usar un algoritmo?
    Un algoritmo es un conjunto de pasos lógicos que nos permiten solucionar un problema o necesidad específicos. A partir de una data de entrada (input), se realiza un proceso y se obtiene una solución (output).
    En el caso de los lenguajes de programación, como las computadoras no razonan, es muy importante detallar cada algoritmo al máximo, indicándo a los ordenadores todos los pasos a seguir de manera explícita.  

2. ¿Cómo un algoritmo mejora el proceso o servicio de una empresa?
    Un algoritmo tiene las siguientes características:
        - Es definido: Su objetivo está bien definido
        - Es preciso: Cada paso está en el orden adecuado y explicado con la mayor cantidad de detalles
        - Es legible: Cada paso es entendible y entendido claramente
        - Es finito: Todo algoritmo tiene un inicio y un final. No puede ser que nunca termine.
    Al hacer uso de algoritmos en una empresa, estamos definiendo explícitamente sus problemas y/o necesidades específicas, y todos los pasos necesarios para resolverlos y/o cubrirlas. Es una manera mucho más ordenada y eficiente de trabajar.
    Además, como los ordenadores son capaces de procesar y almacenar mucha mas data que el cerebro humano, si una empresa se apoya en ellos para resolver sus problemas y/o necesidades, haciendo uso de esta data, puede encontrar solución a un sinfin de problemáticas.  

3. ¿El algoritmo expuesto en este caso es el único con el que cuenta TuTienda?
    Comúnmente, un problema o necesidad puede ser resuelto de distintas maneras. Esto quiere decir que para un mismo objetivo, existen varios algoritmos posibles.
    En el caso de TuTienda, el objetivo principal es el determinar si continuan o no con su servicio de delivery y para esto necesitan calcular las n formas de reducir costos. Este objetivo se puede resolver de distintas formas:
        - Se puede optimizar el servicio de delivery de manera a requerir menos motorizados. Por ejemplo, determinando bien la hora y la zona de entrega, un motorizado podría encargarse de la entrega de varios pedidos en un solo viaje.
        - Se puede hacer el delivery en vehículos que consuman menos combustible como bicicletas o monopatines o a pié. También se puede considerar una combinación de estos métodos, tomando en cuenta la distancia de la zona de entrega.
        - Se puede pagar menos a los motorizados para ahorrar en planilla
        - Se puede subcontratar a un service para el delivery
    Es solamente analizando al detalle cada una de estas opciones, que se puede determinar cuál es la que mas conviene. Cabe señalar que la solución final también podría salir de la combinación de 2 o más de estas opciones.
        


RETO 2

Ejercicios de algoritmos:

1. Implementar un algoritmo que reciba 2 argumentos y los sume, el resultado se deberá imprimir en pantalla
    Algoritmo: cálculo de la suma de 2 números
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese el primer número"
        Leer n1
        Escribir "Ingrese el segundo número"
        Leer n2
        r = n1 + n2
        Escribir "La suma de ambos números es"
        Escribir r
    Fin del algoritmo.

2. Un estudiante realiza 4 exámenes, calcular el promedio de estos
    Algoritmo: cálculo del promedio de 4 exámenes
        Definir n1 como real
        Definir n2 como real
        Definir n3 como real
        Definir n4 como real
        Definir r como real
        Escribir "Ingrese la nota del primer examen"
        Leer n1
        Escribir "Ingrese la nota del segundo examen"
        Leer n2
        Escribir "Ingrese la nota del tercer examen"
        Leer n3
        Escribir "Ingrese la nota del cuarto examen"
        Leer n4
        r = (n1 + n2 + n3 + n4) / 4
        Escribir "El promedio de los cuatro exámenes es"
        Escribir r
    Fin del algoritmo.

3. Calcular el área de un rectángulo
    Algoritmo: cálculo del área de un rectángulo
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese la medida del lado mayor del rectángulo"
        Leer n1
        Escribir "Ingrese la medida del lado menor del rectángulo"
        Leer n2
        r = n1 * n2
        Escribir "El área del rectángulo es"
        Escribir r
    Fin del algoritmo.

4. Calcular el área de un triángulo
    Algoritmo: cálculo del área de un triángulo
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese la medida de la base del triángulo"
        Leer n1
        Escribir "Ingrese la medida de la altura del triángulo"
        Leer n2
        r = n1 * n2 / 2
        Escribir "El área del triángulo es"
        Escribir r
    Fin del algoritmo.  

5. Calcular el área de una circunferencia
    Algoritmo: cálculo del área de una circunferencia a partir del diámetro
        Definir n1 como real
        Definir r como real
        Definir a como real
        Escribir "Ingrese la medida del diámetro de la circunferencia"
        Leer n1
        r = n1 / 2
        a = 3.14159 * (r ^ 2)
        Escribir "Como el radio de la cincunferencia es " r " su área es " a
    Fin del algoritmo.  

6. Determinar el sueldo semanal de un trabajador basándose en sus horas trabajadas y su salario de hora hombre
    Algoritmo: cáculo del sueldo semanal de un trabajador
        Definir t como caracter
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese los nombres y apellidos del trabajador"
        Leer t
        Escribir "Ingrese el salario por hora de este trabajador"
        Leer n1
        Escribir "Ingrese la cantidad de horas trabajadas por este trabajador durante la semana"
        Leer n2
        r = n1 * n2
        Escribir "El sueldo semanal de " t " es " r
    Fin del algoritmo.  

7. Una modista, para realizar sus prendas de vestir, encarga las telas al extranjero. Para cada pedido, tiene que proporcionar las medidas de la tela en pulgadas, pero ella generalmente las tiene en metros. Realice un algoritmo para ayudar a resolver el problema, determinando cuantas pulgadas debe pedir con base en los metros que requiere. Represéntelo mediante el diagrama de flujo y el pseudocódigo (1 pulgada = 0.0254 m).
    Algoritmo: transformación de metros de tela en pulgadas de tela
        Definir n1 como real
        Definir r como real
        Escribir "Ingrese los metros de tela que requiere"
        Leer n1
        r = n1 / 0.0254
        Escribir "Usted requiere " r " pulgadas de tela"
    Fin del algoritmo.  

8. Una empresa importadora desea determinar cuántos dólares puede adquirir con equis cantidad de dinero peruano
    Algoritmo: cambio de divisa de soles peruanos a dólares americanos
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese el tipo de cambio venta del día"
        Leer n1
        Escribir "Ingrese la cantidad de soles peruanos que desea cambiar"
        Leer n2
        r = n2 / n1
        Escribir "Usted recibiría " r " dólares americanos por sus " n2 " soles peruanos, si es que el tipo de cambio venta del día es " n1
    Fin del algoritmo.  

9. Una empresa que contrata personal requiere determinar la edad de las personas que solicitan trabajo, pero cuando se les realiza la entrevista sólo se les pregunta el año en que nacieron
    Algoritmo: cálculo de la edad de una persona a partir de su año de nacimiento     
        Definir n1 como real
        Definir n2 como real
        Definir r como real
        Escribir "Ingrese el año en curso"
        Leer n1
        Escribir "Ingrese el año de nacimiento de la persona de la que desea conocer su edad"
        Leer n2
        r = n1 - n2
        Escribir "Si la persona nació en " n2 " en " n1 " cumple " r " años"
    Fin del algoritmo.

10. Se tiene el nombre y la edad de tres personas. Se desea saber el nombre y la edad de la persona de menor edad
    Algoritmo: en un grupo de 3 personas, determinar que persona es la menor y brindar su nombre y edad  
        Definir p1 como caracter
        Definir n1 como entero
        Definir p2 como caracter
        Definir n2 como entero
        Definir p3 como caracter
        Definir n3 como entero
        Definir n como entero
        Definir p como caracter
        Escribir "Ingrese los nombres y apellidos de la primera persona"
        Leer p1
        Escribir "Ingrese la edad de la primera persona"
        Leer n1
        Escribir "Ingrese los nombres y apellidos de la segunda persona"
        Leer p2
        Escribir "Ingrese la edad de la segunda persona"
        Leer n2
        Escribir "Ingrese los nombres y apellidos de la tercera persona"
        Leer p3
        Escribir "Ingrese la edad de la tercera persona"
        Leer n3
        Si n1 < n2 & n1 < n3
            entonces r = n1
        FinSi
        Si n2 < n1 & n2 < n3
            entonces r = n2
        FinSi
        Si n3 < n1 & n3 < n2
            entonces r = n3
        FinSi
        Si r = n1
		    entonces p = p1
	    FinSi
	    Si r = n2
		    entonces p = p2
	    FinSi
	    Si r = n3
		    entonces p = p3
	    FinSi
        Escribir "La menor de las tres personas tiene " r " años, y es " p
    Fin del algoritmo.

11. Se les dará un bono por antigüedad a los empleados de una tienda. Si tienen un año, se les dará $100; si tienen 2 años, $200, y así sucesivamente hasta los 5 años. Para los que tengan más de 5, el bono será de $1000. Realice un algoritmo y represéntelo ,que permita determinar el bono que recibirá un trabajador
    Algoritmo: determinar el monto del bono que le correponde a los empleados de una tienda según su antiguedad.  
        Definir n1 como entero
        Definir n2 como entero
        Definir b como entero
        Escribir "Ingrese en que año se contrató al emnpleado"
        Leer n2
	    n1 = 2020
	    Si n1-n2 = 0
		    entonces b = 0
	    FinSi
        Si n1-n2 = 1
		    entonces b = 100
	    FinSi
	    Si n1-n2 = 2 
		    entonces b = 200
	    FinSi
	    Si n1-n2 = 3 
		    entonces b = 300
	    FinSi
	    Si n1-n2 = 4 
		    entonces b = 400
	    FinSi
	    Si n1-n2 >= 5 
		    entonces b = 500
	    FinSi
	    Escribir "A este empleado le corresponde un bono de " b
    Fin del algoritmo.

12. Un profesor tiene un salario inicial de $1500, y recibe un incremento de 10 % anual durante 6 años. ¿Cuál es su salario al cabo de 6 años? ¿Qué salario ha recibido en cada uno de los 6 años? Realice el algoritmo y representan la solución, utilizando el ciclo apropiado
    Algoritmo: determinar el salario de un profesor año tras año durante 6 años, considerando un aumento de sueldo de 10% cada año
        Definir n0 como real
        Definir n1 como real
        Definir n2 como real
        Definir n3 como real
        Definir n4 como real
        Definir n5 como real
        n0 = 1500
        n1 = n0 * 1.1
        n2 = n1 * 1.1
        n3 = n2 * 1.1
        n4 = n3 * 1.1
        n5 = n4 * 1.1
        n6 = n5 * 1.1
        Escribir "Si este año el salario del profesor es de 1500:"
        Escribir "En 1 año su salario será " n1
        Escribir "En 2 años su salario será " n2
        Escribir "En 3 años su salario será " n3
        Escribir "En 4 años su salario será " n4
        Escribir "En 5 años su salario será " n5
        Escribir "En 6 años su salario será " n6
    Fin del algoritmo.

13. Realice un algoritmo para leer las calificaciones de N alumnos y determine el número de aprobados y reprobados
    Algoritmo: Calcular cuantos alumnos aprobaron y/o desaprobaron un examen
        Requerir la cantidad de alumnos que se presentaron al examen
        Requerir la nota de cada uno de los alumnos
        Requerir la nota mínima aprobatoria = n
        Calcular cuantos alumnos tuvieron >= a la nota mínima aprobatoria = x
        Carcular cuantos alumnos tuvieron < a la nota mínima aprobatoria = y
        Escribir x " alumnos tuvieron " n " o más. Ellos SI aprobaron el examen"
        Escribir y " alumnos tuvieron menos que " n ". Ellos NO aprobaron el examen"
    Fin del algoritmo.

14. Una compañía, fabrica focos de colores (verdes, blancos y rojos). Se desea contabilizar, de un lote de N focos, el número de focos de cada color que hay en existencia
    Algoritmo: 
        
    Fin del algoritmo.

15. Realice un algoritmo para determinar si una persona puede votar con base en su edad en las próximas elecciones
    Algoritmo: determinar si una persona tiene 18 años o más en el 2021 para que así pueda participar en las elecciones presidenciales 
        Definir n1 como entero
        Definir n2 como entero
        Definir b como entero
        Escribir "Ingrese el año de nacimiento de la persona que quisiera saber si puede participar en las elecciones presidenciales del 2021"
        Leer n2
	    n1 = 2021
	    Si n1-n2 >= 18
		    entonces b = 0
	    FinSi
        Si n1-n2 < 18
		    entonces b = 1
	    FinSi
        Si b = 0
            entonces escribir "Esta persona SI puede votar en las elecciones presidenciales del 2021"
        FinSi
        Si b = 1
            entonces escribir "Esta persona NO puede votar en las elecciones presidenciales del 2021"
        FinSi
    Fin del algoritmo.
