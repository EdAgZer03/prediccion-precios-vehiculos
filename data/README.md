# Datos de vehículos

Utilicé `car_data.csv`, proporcionado por TripleTen para el proyecto académico de Rusty Bargain. El archivo contiene características de anuncios de vehículos y su precio en euros. No incluyo el dataset en este repositorio.

Si tienes acceso al material del proyecto, coloca el archivo en esta carpeta o configura la variable de entorno `CAR_DATA_PATH` con su ruta. El notebook requiere las columnas `Price`, `VehicleType`, `RegistrationYear`, `Gearbox`, `Power`, `Model`, `Mileage`, `FuelType`, `Brand` y `NotRepaired`.

Las variables predictoras son tipo de carrocería, año de matriculación, transmisión, potencia, modelo, kilometraje, combustible, marca y estado de reparación. El objetivo es el precio anunciado, no el precio de cierre de una compraventa.
