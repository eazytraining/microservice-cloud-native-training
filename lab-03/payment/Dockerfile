FROM openjdk:8-jre-alpine 
COPY target/exec/payment-1.0.0-SNAPSHOT-exec.jar /usr/local/lib/payment.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/usr/local/lib/payment.jar"]
