# UnbuntuInContainer

## download latest ubuntu image
`> docker pull ubuntu`

## create the container
`> docker run -t -d ubuntu`

## shell into the image
`> docker exec -it <container_id> /bin/bash`

## update the package sources and install lsb-core 
`> apt update && apt install lsb-core`

## install systemd
`> apt install systemd`

## get ubuntu version
`> lsb_release -a`

## save the state of the container
`> docker commit -p <container_id> my-ubuntu-<version>`
