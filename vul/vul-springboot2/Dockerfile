FROM openjdk:8
WORKDIR /app

COPY build/libs/vul-springboot2.jar /app/app.jar

EXPOSE 8080

ENTRYPOINT java $JAVA_OPTS -jar app.jar