FROM openjdk:8-jdk-alpine 
MAINTAINER "Nithin Reddy Ganji"
ADD LoginModel-0.0.5-SNAPSHOT.war app.war
CMD ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.war"]

