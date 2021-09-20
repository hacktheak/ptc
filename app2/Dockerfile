#Dockerfile for App2 contianer 
FROM tomcat:latest 
COPY ./demo/index.html /usr/local/tomcat/webapps
EXPOSE 8080 
CMD [ "catalina.sh" , "run"]