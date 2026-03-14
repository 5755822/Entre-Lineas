# Entre-Lineas
Es una base de datos diseñada para gestionar de forma sencilla y eficiente los préstamos de una biblioteca universitaria. Permite controlar la disponibilidad de libros, registrar préstamos y devoluciones, y mantener un seguimiento claro del historial de cada usuario.
# Reglas del proyecto
Para que el sistema funcione correctamente: 

No se pueden prestar más libros de los que hay disponibles. 

Una unidad de libro puede estar en muchos préstamos, pero solo uno activo a la vez. 

Un usuario puede prestar muchos libros, pero solo pueden estar registrados en un préstamo a la vez. 

Cada préstamo está relacionado con un único usuario y el libro o los libros. 

Los libros deben presentar su propio estado (disponible, prestado, en mantenimiento, extraviado, etc). 

Cada libro debe tener un id único, a pesar de que sean el mismo título se deben considerar como libros diferentes. 
