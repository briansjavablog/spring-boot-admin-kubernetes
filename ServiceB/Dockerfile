FROM adoptopenjdk/openjdk11
RUN mkdir -p /opt/app
COPY target/ServiceA-0.0.1-SNAPSHOT.jar /opt/app
CMD ["java", "-jar", "/opt/app/ServiceA-0.0.1-SNAPSHOT.jar"]