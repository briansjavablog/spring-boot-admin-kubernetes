FROM adoptopenjdk/openjdk11
RUN mkdir -p /opt/app
RUN mkdir -p /opt/app/logs
COPY target/BootAdminService-0.0.1-SNAPSHOT.jar /opt/app
CMD ["java", "-jar", "/opt/app/BootAdminService-0.0.1-SNAPSHOT.jar"]