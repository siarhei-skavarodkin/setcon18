FROM openjdk:8

RUN mkdir /var/lib/setcon
COPY build/libs/*jar /var/lib/setcon/demo.jar
ENTRYPOINT ["java", "-jar", "/var/lib/setcon/demo.jar"]
