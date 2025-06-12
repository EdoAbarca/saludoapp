# JDK & Maven enviroment
FROM openjdk:17-jdk-slim

RUN apt-get update && \
    apt-get install -y maven git && \
    apt-get clean

RUN java -version && mvn -version
