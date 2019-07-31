FROM openjdk:11

COPY /target/config-server-0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

# Make port 88888 available to the world outside this container
EXPOSE 8888

RUN sh -c 'touch config-server-0.0.1-SNAPSHOT.jar'

ENTRYPOINT ["java","-jar","config-server-0.0.1-SNAPSHOT.jar"]
