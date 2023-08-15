# Docker Note
[Installation](https://docs.docker.com/desktop/install/mac-install/)

[Tutorial](https://docker-curriculum.com/)

## Why Docker?
Isolation and less cost.

## Terms
- *Images* - The blueprints of our application which form the basis of containers.
- *Containers* - Created from Docker images and run the actual application. 
- *Docker Daemon* - The background service running on the host that manages building, running and distributing Docker containers. The daemon is the process that runs in the operating system which clients talk to.
- *Docker Client* - The command line tool that allows the user to interact with the daemon. More generally, there can be other forms of clients too - such as Kitematic which provide a GUI to the users.
- *Docker Hub* - A registry of Docker images. You can think of the registry as a directory of all available Docker images. If required, one can host their own Docker registries and can use them for pulling images.

## Basic Commands
|Command|Description|
|--|--|
|`docker run [image]`|to run a image in a container|
|`docker ps`|to list all running containers|
|`docker ps -a`|to list all containers|
|`docker pull [image]`|to fetch a image from docker registry|
|`docker container prune`|to delete all containers that are stopped|
|`docker rmi`|to delete all the images that no longer needed|

## Airflow With Docker
[Run Airflow in Docker](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html)
[Use Docker and Airflow to Deploy A Model](https://medium.com/sfu-cspmp/use-docker-and-airflow-to-deploy-your-data-science-workflow-dc17982d8dd8)
