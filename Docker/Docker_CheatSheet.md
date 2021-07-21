#The complete docker command cheatsheet

1. **docker --version** - To display the docker version

2. **docker info** - To display the complete docker information which shows the containers, images, networks etc.,

3. **docker system info** - This is same as docker info

4. **docker system prune** - This will remove the redundent images, containers

6. **docker images** - This will list the cpulled images

7. **docker image pull ubuntu:latest** - This will pull the ubuntu latest image from the docker registry

8. **docker search --limit 3 ubuntu** - This will search the top rated ubuntu images with a limit of 3 records

9. **docker image pull -a ubuntu** - This will pull all the specific versions of te image

10. **docker search ubuntu** - This will search the docker images in registry and display the images in an order of most of stars.

11. **docker ps** - This will list the current running containers

12. **docker ps -a** - This will list the current running and stopped containers

13. **docker ps -aq** - This will list the running and stopped containers with only container id.

14. **docker images -q** - This will list the image id's of images.

15. **docker container ls** - This will also list the current running docker containers.

16. **docker logs cont_id** - This will list the logs of the current container

17. **docker logs --tail 3 cont_id** - This will show the last 3 lines of the docker container logs 