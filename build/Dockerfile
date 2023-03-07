FROM ubuntu:20.04
RUN apt update && apt install git -y
RUN DEBIAN_FRONTEND=noninteractive apt-get install maven -y 

RUN git clone https://github.com/elmcslay/DO_edu-HW12_CP.git /tmp/hw12

RUN cd /tmp/hw12 && mvn package