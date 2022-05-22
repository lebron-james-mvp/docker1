FROM java:8-jre
MAINTAINER Jacy <changjing@gcu.edu.cn>

ADD ./target/microservice-gateway-zuul-1.0-SNAPSHOT.jar /app/microservice-gateway-zuul.jar
CMD ["java", "-Xmx200m", "-jar", "/app/microservice-gateway-zuul.jar"]

EXPOSE 8050