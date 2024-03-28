## AlkeWallet
_Base de datos con MySql para una billetera virtual_


Proyecto integrador de una base de datos relacional para una wallet virtual,
Todos sus ejercicios con sus comentarios de cada item dentro de un solo archivo paso a paso.

Situación inicial
📍
Como parte de un equipo de programadores recibiste el pedido de Alke
Wallet de desarrollar el diseño de una base de datos relacional para
gestionar un sistema de una Wallet la cual permitirá a sus usuarios
almacenar y gestionar sus fondos, realizar transacciones y ver el
historial de transacciones. Nuestro líder técnico ya cuenta con los
requerimientos desagregados en un backlog de tareas listo para que
comencemos la etapa de desarrollo.
Nuestro objetivo
📋
El objetivo de esta evaluación es diseñar el modelo conceptual, definir las
relaciones entre las entidades de una wallet y crear la base de datos para
almacenar la información que sea necesaria.
Requerimientos
🤝🏻
La Alke Wallet deberá cumplir con una serie de características y
requerimientos técnicos para garantizar la calidad y funcionalidad de la
misma.
Primero, como requerimiento general tenemos que poder implementar
todas las funcionalidades básicas que un usuario necesita para gestionar
sus fondos, realizar transacciones y ver el historial de transacciones,
las cuales son:
● Diseñar una Bases de Datos que garantice la coherencia y la
integridad de los datos
● Crear una conexión a una Bases de Datos llamada Alke Wallet
● Crear Entidades:1. Usuario: Representa a cada usuario individual del sistema de
monedero virtual.
- Atributos:
user_id (clave primaria)
nombre
correo electrónico
contraseña
saldo.
2. Transacción: Representa cada transacción financiera realizada por los
usuarios.
- Atributos:
transaction_id (Primary Key)
sender_user_id (Foreign Key referenciando a User)
receiver_user_id (Foreign Key referenciando a User)
importe
transaction_date.
3. Moneda: Representa las diferentes monedas que se pueden utilizar
en el monedero virtual.
- Atributos:
currency_id (Primary Key)
currency_name
currency_symbol

Crear consultas SQL para:
- Consulta para obtener el nombre de la moneda elegida por un
usuario específico
- Consulta para obtener todas las transacciones registradas
- Consulta para obtener todas las transacciones realizadas por un
usuario específico
- Sentencia DML para modificar el campo correo electrónico de un
usuario específico
- Sentencia para eliminar los datos de una transacción (eliminado de
la fila completa)
