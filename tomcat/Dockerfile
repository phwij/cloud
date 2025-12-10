FROM tomcat:9.0.82-jdk11
COPY server.xml /usr/local/tomcat/conf/server.xml
COPY webapps/app/test.jsp /usr/local/tomcat/webapps/app/test.jsp
COPY mariadb-java-client-3.0.5.jar /usr/local/tomcat/lib/
EXPOSE 8009
