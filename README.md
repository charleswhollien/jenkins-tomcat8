# jenkins-tomcat8
Ubuntu 18.04 Jenkins Running in Tomcat 8 with DevOps Tools Installed. 

Docker information: 
- JENKINS_HOME set to /jenkins. This should be a volume. 
- Running as user Tomcat8. /var/lib/tomcat8/.ssh/ should include key's if needed for remote access. 
- UID/GID for tomcat8 user/group is 102. 
- Jenkins deploy's at http://HOST:8080/jenkins/

