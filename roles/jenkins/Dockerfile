#mkdir -m 0777 -pv /docker/jenkins/data
#docker run -d -p 8080:8080 -p 50000:50000 --name jenkins --restart=always -v /var/docker/jenkins/data:/var/jenkins_home --network=host jenkins/jenkins:lts

FROM jenkins/jenkins:lts

MAINTAINER wluisaraujo
LABEL maintainer="wluisaraujo"

VOLUME [ "/var/docker/jenkins/data", "/var/jenkins_home" ]

EXPOSE 8080/tcp 
EXPOSE 50000/tcp

