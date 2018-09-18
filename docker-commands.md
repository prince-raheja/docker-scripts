Docker commit -c ‘CMD ${command}’ -t ${tag}   to make a image of a running container


Docker ps —all
Docker ps

Docker images

Docker exec -it ${container_id} bash

Docker start ${container_id}

Docker create ${image_id/name}

Remove all containers -> docker rm $(docker ps -aq)
Remove all images -> docker rmi $(docker images -aq)

-p port_host:port_container for mapping 

Docker run -it     -> to attach stdin to docker image as well
-t just gives you tty (beautiful terminal)
-I interactive 
