FROM eclipse-temurin:17-jdk-alpine
RUN apk add curl
VOLUME /tmp
EXPOSE 8080
ADD target/sprinboot-aws-deploy-service.jar sprinboot-aws-deploy-service.jar
ENTRYPOINT ["java","-jar","sprinboot-aws-deploy-service.jar"]
