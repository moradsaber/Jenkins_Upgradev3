FROM tomcat:8.0
RUN pwd
VOLUME /var/lib/jenkins/workspace/Build_Tomcat_Docker_image/java-tomcat-sample/target/java-tomcat-maven-example.war /usr/local/tomcat/webapps/java-tomcat-maven-example.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
