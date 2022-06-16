FROM tomcat:8.5.69-jdk8-openjdk
WORKDIR /usr/local/tomcat
COPY target/*.war /usr/local/tomcat/webapps
EXPOSE 8080
USER root
CMD chmod +x /usr/local/tomcat/bin/catalina.sh
CMD ["catalina.sh", "run"]
