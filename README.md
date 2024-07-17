# Foro Hub Challenge One Alura Latam

## Funcionalidades

* Permite hacer login ingresando el email y clave de usuario.
* Mediante autenticación es posible realizar operaciones CRUD para cursos, perfiles, usuarios, respuestas, topicos.
* Se genera la documentación de la api mediante Swagger-ui accediendo en el navegador.

## Dependencias (ver pom.xml)

* Swagger
* Lombok
* Flyway
* MySql-connector
* JWT
* Spring (web,security,validation,JPA)
* Versión Java SpringBoot (Initializr) 17

## Funcionamiento

Se requieren crear un usuario con email y su clave en hash de tipo bcrypt en la base de datos y los perfiles.
Posteriormente hacer login y realizar nuevos registros para topicos y respuestas.




