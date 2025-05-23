# Integrantes

Gabriel Escárate

Alex Ibacache

Seccion 2
#Desarrollo

## Diagrama Caso de Uso

![DiagramaCasoUso](https://github.com/user-attachments/assets/93d1de7b-e6df-4581-aba9-08d48bba9810)

### Errores detectados
1- Los actores mal ubicados dentro del caso : **AppReservaExterna** y **SistemaNotificaciones**

2- Los casos no tienen definidas las conexiones: **Extends** e **Include**

3- El **administrador** tiene una coneccion por fuera del container y por debajo de otro actor.


## Diagrama De Clases

![DiagramaClasesMalo](https://github.com/user-attachments/assets/e6fc156a-b0a0-4d85-a8f0-3a64fd634a3c)

### Errores detectados
1- La clase reserva no tiene relacion con el resto del sistema, por lo que no esta siendo utilizada

2- En la implementacion del modelo adpter el **GestorNotificaciones** Debe ser una interfaz y no una clase

3- Falta multiplicidad en las relaciones de las clases. por ejemplo: ¿Un usuario cuantas reeservas puede tener?

## Diagrama Implementacion

![DiagramaImplementacion](https://github.com/user-attachments/assets/e8684116-ee2b-444f-ae92-aa56b36412ff)

1- Falta colocar nombres en las relaciones ejemplo si son **html**, **sql**, **ORM**, etc.
