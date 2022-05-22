FROM java:8-jre
MAINTAINER Jacy <changjing@gcu.edu.cn>
ADD ./target/microservice-userservice-1.0-SNAPSHOT.jar /app/microservice-userservice.jar
CMD ["java", "-Xmx200m", "-jar", "/app/microservice-userservice.jar"]
EXPOSE 8030