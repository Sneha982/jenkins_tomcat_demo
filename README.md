# Jenkins Tomcat Demo

## How to Install Tomcat
Follow below URL to deploy tomcat on Ubuntu 22.04

https://www.digitalocean.com/community/tutorials/how-to-install-apache-tomcat-10-on-ubuntu-20-04


## Steps to Configure Jenkins

- Add SSH Agent and SSH Pipeline Steps plugin
- Tomcat is one server and jenkins is one server- To connect from jenkins server to tomcat we need SSH Agent to copy and deploy the war file into tomcat server.
- sudo chown -R ubuntu:ubuntu /opt/tomcat/
- sudo nano /etc/systemd/system/tomcat.service
- in tomcat.service change below fields
user=ubuntu
#group
