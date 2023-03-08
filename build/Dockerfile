FROM ubuntu:20.04
RUN apt update && apt install git -y
RUN DEBIAN_FRONTEND=noninteractive apt-get install maven -y 

RUN git clone https://github.com/elmcslay/DO_edu-HW12_CP.git
WORKDIR /root/DO_edu-HW12_CP
RUN mvn package

RUN mkdir /tmp/hw12 && cp ./target/App42PaaS-Java-MySQL-Sample.war /tmp/hw12/app.war