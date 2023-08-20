## We are Creating a simple Hello World application with flask
create flask application in app.py with port number 7000
Create Dockerfile with the from python 3.7 with workdir /app.py 
for built docker image creation
```
docker build -t <image_name> .
```
to run image
```
docker run -d -p 7000:8000 <image_name>
```
7000 is the host port and 8000 is the port number of container

To see all the images
```
docker images
```

To remove the image first stop the running image then remove it
```
docker ps
```
```
docker stop <container_Id>
```
```
docker rm <container_id>
```