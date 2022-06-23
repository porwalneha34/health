Hosting a local repo to github using maven.
https://www.baeldung.com/maven-repo-github

install java and maven 



https://linuxize.com/post/how-to-install-apache-maven-on-ubuntu-18-04/



https://www.baeldung.com/maven-repo-github
mvn archtype-generate

https://www.baeldung.com/maven-settings-xml


set pom.xml and settings.xml 


For Jenkins installation in vmbox rhel 8

https://www.redhat.com/sysadmin/install-jenkins-rhel8


https://kbroman.org/github_tutorial/pages/init.html   --> Git project from scratch 

Jenkins setup issue withd docker
error: Cannot run docker commands through Jenkin's Blue Ocean: ERRO[0000] No subuid ranges found for user “jenkins” in /etc/subuid
https://stackoverflow.com/questions/58855758/cannot-run-docker-commands-through-jenkins-blue-ocean-erro0000-no-subuid-ran

sol- echo jenkins:10000:65536 >> /etc/subuid
   echo jenkins:10000:65536 >> /etc/subgid
