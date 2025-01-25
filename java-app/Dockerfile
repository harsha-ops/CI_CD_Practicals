FROM adoptopenjdk/openjdk11:alpine-jre

RUN ls -l

ARG artifact=target/*.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT [ "java", "-jar", "app.jar" ]