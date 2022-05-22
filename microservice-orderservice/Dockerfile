FROM java:8-jre
MAINTAINER Jacy <changjing@gcu.edu.cn>

ADD ./target/microservice-orderservice-1.0-SNAPSHOT.jar /app/microservice-orderservice.jar
CMD ["java", "-Xmx200m", "-jar", "/app/microservice-orderservice.jar"]

EXPOSE 7900