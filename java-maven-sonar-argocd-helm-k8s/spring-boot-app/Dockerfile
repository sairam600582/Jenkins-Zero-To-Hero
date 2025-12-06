FROM adoptopenjdk/openjdk11:alpine-jre

# Simply the artifact path

WORKDIR /opt/app

COPY target/*.jar app.jar

# This should not be changed
CMD ["java","-jar","app.jar"]
