FROM openjdk:8-jre

MAINTAINER yangb <http://yangb.xyz>

COPY target/serve-oauth2-0.0.1-SNAPSHOT.jar /app/app.jar

ENTRYPOINT ["java","-Xmx256m", "-jar","/app/app.jar"]

EXPOSE 9001

