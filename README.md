# jenkins-did
> Jenkins con cliente docker

# Ejecución
```bash
docker run -v /var/run/docker.sock:/var/run/docker.sock \
           -v /var/jenkins_home \
           -p 8080:8080 \
           -d
           romeroyonatan/jenkins-did
```
