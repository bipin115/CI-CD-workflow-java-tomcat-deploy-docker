FROM tomcat:8.0
# Maintainer
MAINTAINER "Bipin Singh" 
# copy war file on to container 
COPY ./java-tomcat-sample-docker.war /usr/local/tomcat/webapps
EXPOSE 8080
CMD ["catalina.sh", "run"]
