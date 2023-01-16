FROM tomcat:8.0-alpine

ADD target/webstore.war /usr/local/tomcat/webapps/ 
ADD pod-network/ContainerCommunication.war /usr/local/tomcat/webapps/ 

ADD change.log /opt/

CMD ["catalina.sh", "run"] 
