# Practica 6.2. Implementación del Repositorio en el Microservicio 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Implementar el repositorio en el microservicio, utilizando Spring Data JPA para gestionar las operaciones de persistencia de manera eficiente.

## Objetivo Visual 
 

## Duración aproximada:
- 45 minutos.

## Tabla de ayuda:
Agregar una tabla con la información que pueda requerir el participante durante el laboratorio, como versión de software, IPs de servers, usuarios y credenciales de acceso.
| Contraseña | Correo | Código |
| --- | --- | ---|
| Netec2024 | edgardo@netec.com | 123abc |

## Instrucciones 

### Tarea 1. Veriricación de acceso a la base de datos MySQL
Paso 1. Varificar que puede tener acceso a la base de datos MySQL

```cmd
mysql -uroot -pNetec_2357 -hlocalhost
```

Paso 2. Verificar las bases de datos creadas

```sql
show databases;
```

Paso 3. <!-- Añadir instrucción -->

### Tarea 2. Modificar los proyectos asociados a los microservicios
Paso 1. Agrega el inicializador
* MySQL Driver
* 
Paso 2. Verifica que tienes el incializador Spring Data JPA

```xml
```
Paso 3. Definr y mapear entidades JPS a las tablas de la base de datos.

Paso 4. Agregar las anotaciones perinentes a la clase Articulo en el microservicio micro-articulo

Paso 5. Crea repositorios JPS para realizar las operaciones CRUD sobre las entidades encontradas.

### Resultado esperado

<div style="text-align: center;">
    <img src="../images/img14_persistencia.png" alt="Persistencia">
</div>



