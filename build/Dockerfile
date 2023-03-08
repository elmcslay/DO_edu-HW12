FROM ubuntu:20.04
RUN apt update && apt install git -y
RUN DEBIAN_FRONTEND=noninteractive apt-get install maven -y 

RUN git clone https://github.com/elmcslay/DO_edu-HW12_CP.git
RUN cd DO_edu-HW12_CP/ && mvn package

RUN mkdir /tmp/hw12 && cp /target/App42PaaS-Java-MySQL-Sample-0.0.1-SNAPSHOT.war /tmp/hw12/app.war