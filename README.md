# DevConnectionDBs
Cosas aprendidas para la conexion a base mediante spring , jdbc y jpa

En este repo estare subiendo lo aprendido para conectar a una base de datos postgre

## 1 Mediante Spring Data JPA 

> En el archivo .pom agregamos las siguientes dependencias


        <dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>

		<dependency>
			<groupId>jakarta.persistence</groupId>
			<artifactId>jakarta.persistence-api</artifactId>
		</dependency>   


> Al actualizar y descargar dependencias, ejecutamos la plicacion y veremos que nos solicita ingresar los parametros de configuracion de la base de datos a utilizar


