FROM tomcat:8.0
#RUN cp -a **/*.war /usr/local/tomcat/webapps/
COPY java-tomcat-sample-docker/target/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
