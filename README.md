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
- $docker run {name}: {tag} - Creates docker container from given image and starts it </br>
``` $docker run nginx:1.25 ```
- $docker run -d {name}: {tag} - Runs the container in background and prints the container ID </br>
``` $docker run -d nginx:1.25 ```
- $docker logs {container}: View logs from service running inside the container (which are present at the time of execution)
``` $docker logs (container_ID) ```
- 
