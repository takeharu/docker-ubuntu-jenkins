#Jenkins Docker Image

###Build
```
$ docker build -t <ImageName> .
```
###Start
```
$ docker run -d --name jenkins -p 8080:8080 takeharu/ubuntu-jenkins
```
###Stop
```
$ docker stop jenkins
```
###Restart
```
$ docker start jenkins
```
