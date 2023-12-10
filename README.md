# Docker Basic
This repo consists of basic docker code that includes installation and operation of Docker in  Windows 11 and Ubutnu 22.04 LTS
## Windows 11
1. Goto https://docs.docker.com/desktop/install/windows-install/. Before downloading make sure your PC meets the "System Requirement" stated in the page. Download Docker desktop installation file.
2. Follow the setup procedure in windows 11.
## Ubuntu 22.04 LTS

----------------------------------------------
### Syntax
- $docker images -Lists docker images </br>
- $docker ps - docker ps [OPTIONS] -Lists docker containers </br>
``` docker ps -a ``` </br>
- $docker pull {image}: {version} - Pull Docker images from container registry </br>
``` $docker pull nginx:1.25 ```
- $docker run {name}: {tag} - Creates docker container from given image and starts it. *Everytime run command is executed, new container of images is created* </br>
``` $docker run nginx:1.25 ```
- $docker run -d {name}: {tag} - Runs the container in background and prints the container ID </br>
``` $docker run -d nginx:1.25 ```
- $docker logs {container}: View logs from service running inside the container (which are present at the time of execution) </br>
``` $docker logs (container_ID) ```
- $docker stop {container}- Stops one or more running container  </br>
``` $docker stop 360e72825dff ```
- $docker run -d -p {host_port}:{containers_port} {image_name}:{image_version} *-p or --publish refers to Publish the container's port to host port*
 ``` $docker run -d -p 6000:80 nginx:1.25 ```
