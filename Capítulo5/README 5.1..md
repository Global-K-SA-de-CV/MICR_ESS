# Práctica 5.1. Creación de un Segundo Microservicio 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Crear y configurar un segundo microservicio que se comunique de manera eficiente con el microservicio de artículos.

## Objetivo Visual:

<div style="text-align: center;">
    <img src="../images/ro7.png" alt="Spring Tool Suite">
</div>


## Duración aproximada:
- 35 minutos.

## Tabla de ayuda:
Los Endpoints podrían ser los siguientes:

| Método | URI/Endpoints                     | Cuerpo  |
|--------|----------------------------------|--------|
| POST   | /carrito  | JSON |
| GET    | /carrito | N/A |


## Instrucciones:

### Tarea 1. Creación de un nuevo proyecto Spring Boot.

**Paso 1.** Crear un nuevo proyecto de tipo Spring Boot: 
* **Name**: micro-carritort
* **Type**: Maven
* **Packaging**: Jar
* **Java Version**: 21
* **Language**: Java
* **Group**: com.netec.micro_carritort
* **Version**: 0.0.1-SNAPSHOT
* **Description**: Implementación del microservicio micro-carritort
* **package**: com.netec.micro_carritort


**Paso 2.** Agrega los inicializadores:

* Spring Web
* Spring Boot Dev Tools

### Tarea 2. Configurar el microservicio de nombre micro-carritort en el puerto 9092.

**Paso 1.** Expande la estructua del proyecto y localiza la carpeta **src/main/resources**.

**Paso 2.** Dentro de esta carpeta, abre el archivo **application.properties**.

**Paso 3.** Agrega la siguiente línea para configurarar el puerto del microservicio a 9092:

```properties
server.port=9092
```

### Tarea 3. Crear la entidad Carrito.

### Tarea 4. Crear la interface ICarritoServicio.

### Tarea 5. Crear la implementación del servicio CarritoServicio.

### Tarea 6. Crear el controlador del microservicio CarritoController.

### Tarea 7. Probar el microservicio:

| Método HTTP | Ruta     | Cuerpo |
|-------------|----------|--------|
| POST        | /carrito |  JSON  |
| GET         | /carrito |   N/A  |

[Inicio](../README.md)<br>
[Práctica 4.2. Configuración, Implementación, Despliegue y Pruebas del Microservicio](../Capítulo4/README 4.2..md)<br>
[Práctica 5.2. Clientes REST declarativos con Feign](../Capítulo5/README 5.2..md)<br>
