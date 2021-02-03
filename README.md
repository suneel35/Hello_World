# Hello_World
=================
GITHUB:
--------

git add .

git commit -m "message"

git remote add origin url

git push origin master

MAVEN :
-------

mvn validate
mvn compile
mvn test
mvn test
mvn package
mvn install
mvn deploy

Apache Tomcat Server
-------------------

how to start the server    ./startup.sh
how to create a user   tomcat-users.xml
how to change port number server.xml
Actually default network is accessed thats why we can change the META-INF directory comment to valves 2 Lines


Docker :  Docker is a Developer and Sysadmin build,ship,run different applications
--------
Docker file to Create Image

docker build -t imagename .

Docker Image to create tag

docker tag srcfile destfile

Docker registry (Doccker Image) to create container

docker run -d -p 5000:5000 --name containername imagename

After container created access to IPADDRESS:hostPort/packagename 
