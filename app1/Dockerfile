#Dockerfile for the App1 container 
FROM tomcat:latest 
COPY ./student.war /usr/local/tomcat/webapps
EXPOSE 8080 
CMD [ "catalina.sh" , "run"]