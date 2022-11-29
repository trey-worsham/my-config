# my config
a repository that contains my personal Linux configs

## alpine linux
to start the container i run
```
docker run -d -t --name alpine_linux alpine /bin/sh
```
then once in the container i run
```
apk update && apk upgrade && apk add bash && apk add git && git clone https://github.com/trey-worsham/my-config.git && cd my-config && bash start_alpine_in_docker.sh
```
## temux
```
pkg update && pkg upgrade && pkg install git && git clone https://github.com/trey-worsham/my-config.git && cd my-config && bash start_temux.sh
```

## ubuntu in docker
to start the container i run
```
docker run -d -t --name ubuntu_linux ubuntu 
```
then once in the container i run
```
apt update && apt upgrade -y && apt install git -y && git clone https://github.com/trey-worsham/my-config.git && cd my-config && bash start_ubuntu_in_docker.sh
```
