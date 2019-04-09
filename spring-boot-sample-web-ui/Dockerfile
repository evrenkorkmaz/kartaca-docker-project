FROM openjdk:8-slim
ADD target/spring-boot-sample-web-ui.jar  spring-boot-sample-web-ui.jar
EXPOSE 7000
ENTRYPOINT ["java" , "-jar" , "spring-boot-sample-web-ui.jar" ,"--server.port=7000" , "--server.servlet.context-path=/ui" ]
