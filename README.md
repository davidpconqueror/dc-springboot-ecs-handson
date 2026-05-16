# Springboot-App_Deployment

This is a sample microservice to deploy it on AWS ECS.

Health Check command for AWS Task definition : 
```
CMD-SHELL,curl -f http://localhost:8080/actuator/health || exit 1
```
Prereq to start this project :- 
1. AWS account.
   
2. Git and docker installed on the machine.
   
3. Docker should be started before building docker image.

