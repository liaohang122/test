FROM openjdk:8u201-jdk-alpine
ENV APP_FILE user-mgmt-be.jar
ENV APP_HOME /usr/app
ENV LOG_DIR /usr/app/log
EXPOSE 8067
COPY ./${APP_FILE} $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["java","-jar", "user-mgmt-be.jar"]
