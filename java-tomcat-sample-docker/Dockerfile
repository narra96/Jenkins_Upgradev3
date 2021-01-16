FROM tomcat:8.0
ADD cp -a **/*.war /usr/local/tomcat/webapps/
#addsthe tomcat war file and copy this artifact at pat as mentioned 
EXPOSE 8080
#portmachine number make sure it is not  open on docker 
CMD ["catalina.sh", "run"]
#from dockerhub we can see the tomact image usage for clarification 
