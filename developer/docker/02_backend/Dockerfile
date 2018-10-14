FROM java:8
MAINTAINER noway0032 <noway0032@gmail.com>
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
RUN mvn clean package 
RUN java -jar target\babydiary.jar
EXPOSE 8080 80