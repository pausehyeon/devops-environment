FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY billtracker/build/libs/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
