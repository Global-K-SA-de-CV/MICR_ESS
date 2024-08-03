# Practica 6.3. Configuración de la Persistencia 

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Configurar las propiedades necesarias en el archivo de propiedades, para establecer la conexión con una base de datos relacional.

## Objetivo Visual 
Crear un diagrama o imagen que resuma las actividades a realizar, un ejemplo es la siguiente imagen. 

![diagrama1](../images/img1.png)

## Duración aproximada:
- 30 minutos.

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
show databases
```

Paso 2. Agrega las siguientes líneas para configurarar el acceso a la base de datos

```properties
# Lineas para MySQL
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://<ip_address>:3306/micro_articulo_bd
spring.datasource.username=root
spring.datasource.password=Netec_2357
```

### Resultado esperado
En esta sección se debe mostrar el resultado esperado de nuestro laboratorio
![imagen resultado](../images/img3.png)


