FROM openjdk:11

COPY /target/microservicesRegistrationServer-0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

# Make port 8761 available to the world outside this container
EXPOSE 8761

RUN sh -c 'touch microservicesRegistrationServer-0.0.1-SNAPSHOT.jar'

ENTRYPOINT ["java","-jar","microservicesRegistrationServer-0.0.1-SNAPSHOT.jar"]
