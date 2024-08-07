# Práctica 6.1. Definición del Esquema de la Base de Datos que Soporte el Microservicio 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Definir y estructurar el esquema de la base de datos que soporte el microservicio.


## Duración aproximada:
- 40 minutos.


## Instrucciones 

### Tarea 1. Identificación de entidades para los microservicios: micro-articulo & micro-carritof

**Paso 1.** Identificar las entidades clave para los microservicios hasta este momento creados.


**Paso 2.** Varificar que puede tener acceso a la base de datos MySQL

```cmd
mysql -uroot -pNetec_2357 -hlocalhost
```

**Paso 3.** Crear una base de datos para micro-articulo y otra instancia de base de datos para micro-carrito

```sql
show databases;
create database micro_articulo_bd;
create database micro_carrito_bd;
```

 


