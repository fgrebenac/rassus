FROM openjdk:11-jre-slim
LABEL maintainer=filipgrebenac
WORKDIR /app
COPY libs libs/
COPY resources resources/
COPY classes classes/
ENTRYPOINT ["java", "-cp", "/app/resources:/app/classes:/app/libs/*", "hr.fer.rasus.TemperatureMicroserviceApplication"]
EXPOSE 8080
