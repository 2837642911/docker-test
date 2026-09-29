FROM eclipse-temurin:17-jre
LABEL maintainer="jiangkaibin"
WORKDIR /app

ADD target/demo-0.0.1-SNAPSHOT.jar /app/demo-0.0.1-SNAPSHOT.jar
EXPOSE 8097
ENTRYPOINT ["java" ,"-Xms256m", "-Xmx512m","-jar","//app/demo-0.0.1-SNAPSHOT.jar"]
