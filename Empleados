/*Creacion de base de datos*/
CREATE DATABASE Empresa;

/*Creacion de tabla y agregar informacion*/
USE Empleados;
CREATE TABLE Empleados (
    Id_empl INT AUTO_INCREMENT PRIMARY KEY,
    Nombre VARCHAR(50),
    Cargo VARCHAR(50),
    Salario  INT);

INSERT INTO Empleados (nombre, cargo, salario) VALUES
    ('Juan Pérez', 'Gerente', 7500000),
    ('Ana Gómez', 'Desarrollador', 6000000),
    ('Luis Castro', 'Proyectos', 10000000);

/*Creacion de tabla y agregar informacion*/
CREATE TABLE Cargo (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nombre_cargo VARCHAR(50),
    salario INT,
    descripcion VARCHAR(255));

USE Empresa;
INSERT INTO Cargo (Nombre_cargo, Salario, Descripcion) VALUES
    ('Gerente', 500000, 'Responsable de la gestión y dirección general'),
    ('Asistente', 250000, 'Soporte administrativo y asistencia'),
    ('Desarrollador', 400000, 'Desarrollo de software y soluciones tecnológicas');


/*Consultas a BD Empresa*/

-	Seleccionar todos los cargos:

USE Empresa;
SELECT	
	Nombre_cargo
	FROM Cargo


/*Seleccionar empleados que ganan más de 7,000,000:*/

	USE Empresa;
	SELECT	
			Nombre
	FROM Empleados
	WHERE
			salario > 7000000


-	Actualizar el salario de un empleado (por ejemplo, de 'Ana Gómez'): se quiere aumentar el salario de 'Ana Gómez' a 6,500,000:

UPDATE Empleados
	SET 
  	      salario = 6500000
WHERE nombre = 'Ana Gómez';


-	Eliminar un empleado (por ejemplo, 'Luis Castro'):

	USE Empresa;
DELETE FROM Empleados
WHERE nombre = 'Luis Castro';

-	Seleccionar empleados con el cargo 'Desarrollador':

	USE Empresa;
	SELECT	
			Nombre
	FROM Empleados
	WHERE
		   Cargo IN ('Desarrollador')

-	Insertar un nuevo empleado con un cargo existente: se quiere agregar a 'Marta López' con el cargo de 'Asistente' y un salario de 3,000,000:

	USE Empresa;
	INSERT INTO Empleados (nombre, cargo, salario) 
VALUES ('Marta Lopez', 'Asistente', 3000000);

















