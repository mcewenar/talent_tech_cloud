#FALLA EL CONTENEDOR Y SE FRENA:

FROM openjdk:8-jdk-alpine3.9
RUN apk update
RUN addgroup -S appgroup && adduser -S appuser -G appgroup
USER appuser
EXPOSE 8080
COPY . /usr/src/myapp
#ADD target/spring-boot-docker.jar spring-boot-docker.jar
#ENTRYPOINT [ "java", "-jar", "/spring-boot-docker.jar" ]


#FROM openjdk:17
#RUN apk update
#RUN addgroup -S appgroup && adduser -S appuser -G appgroup
#COPY . /usr/src/myapp
#WORKDIR /usr/src/myapp
#USER appuser
#RUN javac Main.java
#CMD ["java", "Main"]
#EXPOSE 8080






