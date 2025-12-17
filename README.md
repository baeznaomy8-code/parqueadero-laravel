# ParkingExpress – Sistema de Parqueadero

## Descripción del proyecto
ParkingExpress es un sistema web desarrollado en Laravel que permite registrar y gestionar los vehículos que ingresan a un parqueadero. El sistema reemplaza el registro manual en papel y facilita el control de entradas y salidas de vehículos.

## Caso de uso
El sistema está diseñado para el administrador del parqueadero, quien necesita:
- Registrar vehículos al momento de su ingreso
- Ver el listado de vehículos dentro del parqueadero
- Editar información en caso de errores
- Marcar la salida de un vehículo
- Usar el sistema desde computadora o celular

## Funcionalidades principales
- Registro de vehículos (placa, tipo, propietario y observaciones)
- Fecha y hora de ingreso automática
- Listado de vehículos activos
- Edición de registros
- Eliminación lógica (salida del vehículo)
- Interfaz responsive para dispositivos móviles

## Arquitectura utilizada
Se utilizó la arquitectura MVC (Modelo - Vista - Controlador):
- Modelo: Vehiculo
- Vista: Blade Templates
- Controlador: VehiculoController

Esta arquitectura permite separar la lógica de negocio, la interfaz y el acceso a datos.

## Base de datos
Se utilizó MySQL como gestor de base de datos por su integración con Laravel y facilidad de uso.

## Decisiones de diseño
- Se utilizó Bootstrap 5 para una interfaz responsive
- La hora de ingreso se registra automáticamente
- El propietario es un campo opcional
- La salida del vehículo se maneja mediante eliminación del registro
- El sistema es accesible desde dispositivos móviles

## Requisitos técnicos
- Laravel Herd
- PHP
- MySQL
- Bootstrap 5
- GitHub

## Instrucciones para ejecutar el proyecto
1. Clonar el repositorio
2. Configurar el archivo `.env`
3. Ejecutar las migraciones:

## Acceder al sistema desde: 
http://parqueadero.test
