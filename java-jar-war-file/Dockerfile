
FROM tomcat:8.0-jre8 


ADD sample.war /usr/local/tomcat/webapps/
RUN chmod +x /usr/local/tomcat/webapps/
EXPOSE 8080

CMD [“catalina.sh”, “run”]
