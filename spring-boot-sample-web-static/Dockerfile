FROM openjdk:8-slim
ADD target/spring-boot-sample-web-static.jar spring-boot-sample-web-static.jar
EXPOSE 7070
ENTRYPOINT ["java", "-jar" , "spring-boot-sample-web-static.jar" ,"--server.port=7070" ]
