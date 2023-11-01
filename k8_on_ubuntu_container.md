## run ubuntu docker image
`> docker run -d --privileged my-ubuntu-22.04.3'

## update and upgrade apt
`> apt update`
`> apt upgrade`

## install docker
`> apt install docker.io`

## confirm docker
`> docker --version`

## enable docker service
`> systemctl enable docker`

## add kubernetes signing key 
curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | apt-key add

