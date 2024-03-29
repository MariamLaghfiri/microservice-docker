FROM openjdk:17
WORKDIR /app
COPY target/service-post-0.0.1-SNAPSHOT.jar /app/app-1.0.0.jar
ENTRYPOINT ["java","-jar","app-1.0.0.jar"]