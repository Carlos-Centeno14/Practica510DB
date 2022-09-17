Codigo de la base de datos necesaria para el software
----------------------------------------------
create database actividad510;
use actividad510;
create table productos(
id_producto int primary key not null,
nombre varchar(80),
descripcion varchar(100),
precio double
);
insert into productos(id_producto, nombre, descripcion, precio) values
(1,'Sabritas naturales','Sabritas amarillas',17.50),(2,'Coca-Cola','2.5 litros',39.50),
(3,'Pan de caja','Bimbo',30.00),(4,'Paleta de la rosa','Chica',3.50),
(5,'Jabon Zote','medio kilo',40.00),(6,'Donas-Artesanales','Chocolate',6.50),
(7,'Chicles','Clorets',2.50),(8,'Donas bimbo','Espolvoreadas',25.00),(9,'Nito','Bimbo',10.00),
(10,'Cigarros','Malboro',50.00);
