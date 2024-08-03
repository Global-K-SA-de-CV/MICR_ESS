# Práctica 6.1. Definición del Esquema de la Base de Datos que Soporte el Microservicio 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Definir y estructurar el esquema de la base de datos que soporte el microservicio.

## Objetivo Visual 
Crear un diagrama o imagen que resuma las actividades a realizar, un ejemplo es la siguiente imagen. 

![diagrama1](../images/img1.png)

## Duración aproximada:
- 40 minutos.

## Tabla de ayuda:
Agregar una tabla con la información que pueda requerir el participante durante el laboratorio, como versión de software, IPs de servers, usuarios y credenciales de acceso.
| Contraseña | Correo | Código |
| --- | --- | ---|
| Netec2024 | edgardo@netec.com | 123abc |

## Instrucciones 

### Tarea 1. Identificación de entidades para los microservicios: micro-articulo & micro-carritof
Paso 1. Identificar las entidades clave para los microservicios hasta este momento creados.

Paso 2. Varificar que puede tener acceso a la base de datos MySQL

```cmd
mysql -uroot -pNetec_2357 -hlocalhost
```

Paso 3. Crear una base de datos para micro-articulo

```sql
show databases;
create database micro_articulo_bd;
create database micro_carrito_bd;
```

### Resultado esperado
En esta sección se debe mostrar el resultado esperado de nuestro laboratorio
![imagen resultado](../images/img3.png)


