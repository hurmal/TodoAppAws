FROM openjdk:11.0.9.1-jre

COPY --from=build target/TodoAppAws-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]
