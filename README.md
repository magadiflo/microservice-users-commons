# Sobre el curso
Tomado de **[Microservicios con Spring Boot y Spring Cloud Netflix Eureka](https://www.udemy.com/course/microservicios-con-spring-boot-y-spring-cloud/)**, 
para complementar el contenido seguido del libro: **Microservicios, un enfoque integrado**

# Crear la librería
Desde el cmd, en la raíz del proyecto ejecutamos el comando de abajo. Ese comando generará el .jar del proyecto.

```
 mvnw install
```

El jar generado anteriormente se guardará en 

```
C:\Users\USUARIO\.m2\repository\com\magadiflo\users\commons\microservice-users-commons\0.0.1-SNAPSHOT
```

# Importante
Como el microservice-users y microservice-users-commons tenían el mismo nombre del package base, es que
al momento de generar la librería del microservice-users-commons y agregarla en el otro microservicio, esta no funcionaría.
Por eso es que se renombró el package de microservice-users-commons para que no sea igual al del microserice-users
