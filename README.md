In this repository, I used the [ https://github.com/spring-guides/gs-spring-boot.git]( https://github.com/spring-guides/gs-spring-boot.git) project to buld a multi-stage image to build and run the project.

#### To build locally in your machine:
clone the repository - 
`git clone https://github.com/AnwarHb/gs-docker.git`

move to repository:
`cd gs-docker`

Build the image:
`docker build -t gs-docker`

#### To run the image locally :
`docker run -d -p 8080:8080 gs-docker`

#### or you can access the image in DockerHub:
`docker pull anwarhb/gs-boot`

To run the image:
`docker run -d -p 8080:8080 anwarhb/gs-boot`

[![](https://github.com/AnwarHb/gs-docker/blob/main/docker_latest.png?raw=true)](https://github.com/AnwarHb/gs-docker/blob/main/docker_latest.png?raw=true)

you can see two tags for the image:
[![](https://github.com/AnwarHb/gs-docker/blob/main/docker_tags.png?raw=true)](https://github.com/AnwarHb/gs-docker/blob/main/docker_tags.png?raw=true)
