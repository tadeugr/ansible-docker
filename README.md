http://34.217.247.137:3000/

docker exec -it ansibledocker_ansible_1 bash

wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u161-b12/2f38c3b165be4555a1fa6e98c45e0808/jdk-8u161-linux-x64.tar.gz
export JAVA_HOME=/opt/jdk1.8.0_161/ 
export PATH=$PATH:/opt/jdk1.8.0_161/bin/

http://mirrors.jenkins.io/war-stable/latest/jenkins.war
java -jar jenkins.war --httpPort=8080


apt-get update
apt-get install -y apt-transport-https ca-certificates curl gnupg2 software-properties-common
curl -fsSL https://download.docker.com/linux/debian/gpg | apt-key add -
apt-key fingerprint 0EBFCD88
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian $(lsb_release -cs) stable"
apt-get update
apt-get install -y docker-ce




https://github.com/shazChaudhry/docker-jenkins/blob/ee0f386fd1706829b956cb2e723c0f2935496933/Dockerfile
https://emilwypych.com/2017/10/29/how-to-run-jenkins-with-docker/
