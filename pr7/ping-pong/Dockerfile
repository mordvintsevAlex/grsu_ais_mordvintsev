FROM ubuntu:20.04
RUN apt-get update && apt-get install -y default-jdk
COPY PingPongMORDVINSEV.java /
RUN javac PingPongMORDVINSEV.java
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["PingPongMORDVINSEV"]
