# ubuntu in docker
to start the container i run
```
docker run -d -t --name linux ubuntu 
```
then once in the container i run
```
apt update && apt upgrade -y && apt install git -y && git clone https://github.com/trey-worsham/my-config.git && cd my-config && bash start_ubuntu_in_docker.sh
```
