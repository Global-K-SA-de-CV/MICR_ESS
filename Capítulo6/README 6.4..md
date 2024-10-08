# Practica 6.4. Pruebas de la Persistencia del Microservicio en la Base de Datos 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Realizar pruebas de persistencia del microservicio en la base de datos.

## Objetivo Visual:

<div style="text-align: center;">
    <img src="../images/ro12.png" alt="Spring Tool Suite">
</div>

## Duración aproximada:
- 45 minutos.

## Instrucciones: 

### Tarea 1. Levantar el microservicio: micro-articulo.
**Paso 1.** Iniciar el microservicio.

* Asegúrate de que el microservicio micro-articulo esté configurado correctamente y ejecútalo en tu entorno de desarrollo.

**Paso 2.** Verificar la existencia de las tablas en MySQL:

* Abre una terminal y conecta a la base de datos MySQL:

```cmd
mysql -hlocalhost -uroot -pabcd_2357
```

* Selecciona la base de datos micro_articulo_bd:
   
```sql
use micro_articulo_bd;
```
* Muestra las tablas para verificar que la tabla artículos exista:

```sql
show tables;
```
* Consulta los datos en la tabla articulos:

```sql
select * from artículos;
```


**Paso 3.** Abre Postman y realiza una solicitud POST al endpoint /api/articulos.

* Repite el proceso para agregar varios artículos.

**Paso 4.** Verificar los artículos en la base de datos.

*En la terminal de MySQL, consulta nuevamente la tabla articulos para verificar que los nuevos artículos se hayan ingresado correctamente:

```sql
select * from artículos;
```


### Tarea 2. Levantar el microservicio: micro-carritof.

**Paso 1.** Iniciar el microservicio.

**Paso 2.** Agregar varios articulos al carrito usando Postman/Insomia.

**Paso 3.** Verifica la descripción de los articulos en el carrito.

[Inicio](../README.md)<br>
[Practica 6.3. Configuración de la Persistencia](../Capítulo6/README 6.3..md)<br>
