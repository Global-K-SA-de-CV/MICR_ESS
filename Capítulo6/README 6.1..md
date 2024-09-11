# Práctica 6.1. Definición del Esquema de la Base de Datos que Soporte el Microservicio 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Definir y estructurar el esquema de la base de datos que soporte el microservicio.

## Objetivo Visual:

<div style="text-align: center;">
    <img src="../images/ro9.png" alt="Spring Tool Suite">
</div>


## Duración aproximada:
- 40 minutos.


## Instrucciones: 

### Tarea 1. Identificación de entidades para los microservicios: micro-articulo & micro-carritof.

**Paso 1.** Identificar las entidades clave para los microservicios hasta este momento creados.


**Paso 2.** Varificar que se puede tener acceso a la base de datos MySQL:

```cmd
mysql -uroot -pNetec_2357 -hlocalhost
```

**Paso 3.** Crear una base de datos para micro-articulo y otra instancia de base de datos para micro-carrito:

```sql
show databases;
create database micro_articulo_bd;
create database micro_carrito_bd;
show databases;
```

 [Inicio](../README.md)<br>
[Práctica 5.3. Pruebas de la Comunicación entre Microservicios](../Capítulo5/README 5.3..md)<br>
[Practica 6.2. Implementación del Repositorio en el Microservicio](../Capítulo6/README 6.2..md)<br>
