FROM openjdk:8
ADD target/docker-app-config-server.jar docker-app-config-server.jar
EXPOSE 8040
ENTRYPOINT ["java","-jar","docker-app-config-server.jar"]