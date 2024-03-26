---
runme:
  id: 01HSXN4VHKFZ2X68MH67B9HTGH
  version: v3
---

# training-rahmat-junaid

Issues - 



Docker exercise 1 

If seeing the followign error when trying to push docker image to hub"

denied: requested access to the resource is denied


Then do 'docker login' and login to docker hub via this 


Docker exercise 2 


DOckerfile fixed to: 
FROM openjdk:8-jdk-alpine

To build the Dockerfile:
docker build . -t java-pingpong  

To run the image:
docker run -d -p 1985:8080 java-pingpong


To test the container has run go to 

loclahost[port]/ping

Exercise 3 


 docker build -t python-app .