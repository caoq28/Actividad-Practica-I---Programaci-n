# Actividad Practica I Programación

En esta actividad, se desarrolla un programa informático orientado a la gestión de información de clientes en un consultorio odontológico. Su objetivo principal es capturar, procesar y organizar datos básicos de los pacientes que solicitan servicios con el odontologo.

Inicialmente, el programa debe permitir el ingreso de información fundamental de cada cliente, como su número de cédula, nombre, teléfono, dirección, tipo de cliente (ya sea particular, afiliado a EPS o medicina prepagada), tipo de atención requerida (limpieza, calzas, extracción o diagnóstico), cantidad del servicio, prioridad de atención (normal o urgente) y la fecha de la cita.

A partir de estos datos, el sistema calcula el valor de cada cita, teniendo en cuenta que cada una de estas incluye un único tipo de atención y que la cantidad varía según el procedimiento: para limpieza y diagnóstico siempre es 1, mientras que para calzas y extracciones puede ser mayor que cero, por lo tanto el valor total a pagar por el cliente se obtiene sumando el costo base de la cita más el costo del servicio multiplicado por la cantidad solicitada.

Además, el programa debe ser capaz de almacenar la información de múltiples clientes en una estructura de datos, como un arreglo en memoria. Con estos datos almacenados, se deben realizar algunos cálculos adicionales, como el total de clientes atendidos, los ingresos totales obtenidos y la cantidad de clientes que requieren extracciones dentales.

Por otra parte, se debe implementar un proceso de ordenamiento que permita organizar la lista de clientes de acuerdo con el valor de la atención, de mayor a menor. Finalmente, el programa debe incluir una función de búsqueda que permita encontrar un cliente específico a partir de su número de cédula dentro de la lista ordenada.

Integrando el uso de estructuras básicas de programación, manejo de datos, cálculos aritméticos, almacenamiento en memoria, ordenamiento y búsqueda, con el fin de simular un sistema sencillo de gestión para un consultorio odontológico.

Camila Andrea Oquendo Quintero