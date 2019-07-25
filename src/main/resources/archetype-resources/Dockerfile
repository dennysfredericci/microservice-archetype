FROM adoptopenjdk/openjdk11:latest

ENTRYPOINT ["java", "-jar", "/app/${artifactId}.jar"]

ARG JAR_FILE
ADD target/${JAR_FILE} /app/${artifactId}.jar