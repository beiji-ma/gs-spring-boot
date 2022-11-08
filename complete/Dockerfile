FROM openjdk:8u232-jdk 
WORKDIR /app 
LABEL maintainer="beijim" app="devops-demo" 
COPY target/spring-boot-complete-0.0.1-SNAPSHOT.jar devops-demo.jar 
EXPOSE 8080 
CMD java -jar devops-demo.jar 
