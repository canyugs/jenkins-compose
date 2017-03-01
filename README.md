This Project is clone from maxfields2000/dockerjenkins_tutorial

這是 Tera 用的 Jenkins

# Container include 

 - Jenkins (jenkins-master)
 - nginx   (jenkins-nginx)
 - data    (jenkins-data)
 - theme   (jenkins-theme) // for Web theme
 - slave   (jenkins-slave) // Not use

# Run docker-compose

1. make build
2. make run

# Update jenkins version

vim /home/jenkins/jenkins-compose/jenkins-master/Dockerfile

這個目錄下 /home/jenkins/jenkins-compose/   
1. make build
2. make run
