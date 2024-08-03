# Practica 6.4. Pruebas de la Persistencia del Microservicio en la Base de Datos 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Realizar pruebas de persistencia del microservicio en la base de datos.

## Objetivo Visual 
Crear un diagrama o imagen que resuma las actividades a realizar, un ejemplo es la siguiente imagen. 

![diagrama1](../images/img1.png)

## Duración aproximada:
- 45 minutos.

## Tabla de ayuda:
Agregar una tabla con la información que pueda requerir el participante durante el laboratorio, como versión de software, IPs de servers, usuarios y credenciales de acceso.
| Contraseña | Correo | Código |
| --- | --- | ---|
| Netec2024 | edgardo@netec.com | 123abc |

## Instrucciones 

### Tarea 1. Levantar el microservicio: micro-articulo
Paso 1. Iniciar el microservicio

* Asegúrate de que el microservicio micro-articulo esté configurado correctamente y ejecútalo en tu entorno de desarrollo.

Paso 2. Verificar la existencia de las tablas en MySQL

* Abre una terminal y conecta a la base de datos MySQL

```cmd
mysql -hlocalhost -uroot -pabcd_2357
```

* Selecciona la base de datos micro_articulo_bd:
   
```sql
use micro_articulo_bd;
```
* Muestra las tablas para verificar que la tabla artículos existe:

```sql
show tables;
```
* Consulta los datos en la tabla articulos:

```sql
select * from artículos;
```

Paso 3. Abre Postman y realiza una solicitud POST al endpoint /api/articulos
* Repite el proceso para agregar varios artículos.

Paso 4. Verificar los artículos en la base de datos.

*En la terminal de MySQL, consulta nuevamente la tabla articulos para verificar que los nuevos artículos se hayan ingresado correctamente.

```sql
select * from artículos;
```


### Tarea 2. Levantar el microservicio: micro-carritof
Paso 1. Iniciar el microservicio

Paso 2. Agregar varios articulos al carrito usando Postman/Insomia

Paso 3. Verifica la descripción de los articulos en el carrito.

### Resultado esperado
En esta sección se debe mostrar el resultado esperado de nuestro laboratorio
![imagen resultado](../images/img3.png)


