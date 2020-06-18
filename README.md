This is Dockerfile for run Docker in Docker Jenkins.

1. First step you should create docker image based oj thie docker file

2. For start to work you should run this docker with next parameters:

docker run -v /var/run/docker.sock:/var/run/docker.sock --name jenkins name-of-image

