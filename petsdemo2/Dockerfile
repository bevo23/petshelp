FROM openjdk:21


ARG JAR_FILE=target/*.jar


COPY ${JAR_FILE} petsdemo.jar




ENTRYPOINT [ "java",  "-jar", "/petsdemo.jar"]