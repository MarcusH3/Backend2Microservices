FROM openjdk:17
VOLUME /tmp
ARG JAR_FILE=build/libs/item-micro.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","/app.jar"]