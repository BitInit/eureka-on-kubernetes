FROM openjdk:8-jre-alpine
COPY eureka-1.0.0-SNAPSHOT.jar /usr/local/rtrs/eureka.jar
WORKDIR /usr/local/rtrs

RUN echo "Asia/Shanghai" > /etc/timezone

EXPOSE 8761
CMD ["sh", "-c", "java ${JVM_OPTS} -jar /usr/local/rtrs/eureka.jar"]