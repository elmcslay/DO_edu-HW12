FROM maven:3.9-ibmjava-8
RUN apt update && apt install git -y

RUN git clone https://github.com/elmcslay/DO_edu-HW12_CP.git

RUN cd DO_edu-HW12_CP/ && mvn package