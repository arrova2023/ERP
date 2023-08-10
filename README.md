# ERP

# Sistema-ventas-spring-boot
 Un sistema de ventas usando Java, Spring MVC, MySQL y Bootstrap

# POS con Spring Boot

# Tutorial

## Descargar código del sistema de ventas Spring Boot y compilar

Si quieres puedes clonar el repositorio, he usado gradle para todo así que puedes usar incluso el bloc de notas para programar.

Lo que tienes que hacer es instalar gradle, MySQL y Java; es decir, todo lo necesario para programar con Spring Boot y MySQL.

Después ejecuta el programa con:

`gradlew bootRun`

Y crea el jar usando:

`gradlew build`

También puedes importar el proyecto usando IntelliJ IDEA.

Después ejecuta el jar con:

`java -jar nombre-del-jar.jar`

En ambos casos (ya sea que estés ejecutando el sistema para programar, o ejecutes el jar) visita _http://localhost:8080/productos/mostrar_.

No olvides que dejo el código fuente en GitHub.

Más información sobre Spring Boot y Gradle aquí.

## Tu propio application.properties para mi sistema de ventas con Spring Boot

Si mi contraseña, usuario o configuración no son acorde a tus requisitos recuerda que siempre puedes crear un archivo llamado `application.properties` en el **mismo directorio** en donde está el jar, así, será tomado en cuenta ese archivo en lugar del mío.

## Esquema de base de datos
No es necesario proporcionar el esquema de la base de datos pues la migración se hace automáticamente al ejecutar el proyecto; sin embargo se puede encontrar un esquema en src/main/resources/

Te aviso que probablemente cause algunos errores si la base de datos del proyecto no está limpia

