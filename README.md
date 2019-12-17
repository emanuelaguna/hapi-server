# hapi-server
Create a hapi app from scratch 

This a simple hapi server running on docker container

To run
First build image

$ docker build -t hapi-server . 

Then to run container

$ docker container run --rm -p 3030:3030 <image-id>
