#Dockerfile for the App1 container 
FROM tomcat:latest 
COPY ./demo/index.html /usr/local/tomcat/webapps
EXPOSE 8080 
CMD [ "catalina.sh" , "run"]