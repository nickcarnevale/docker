# Basics

```sh
#to view images
docker images

#to see current containers' status
docker ps

#to see current and past containers
docker ps -a

#to run an image in a container interactively
#this will open up a cli for your container
docker run -it <image>

#to name the container whatever you would like
docker run -it <image> --name <name>

#to stop a container 
docker stop <name>

#to remove a container
docker rm <name>
```




