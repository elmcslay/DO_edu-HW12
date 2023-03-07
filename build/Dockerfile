FROM maven:3-ibmjava-8
RUN apt update && apt install git -y

RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git

RUN cd boxfuse-sample-java-war-hello/ && mvn package