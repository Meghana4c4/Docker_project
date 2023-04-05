# project
from EC2 Ubuntu Instance(AWS)
Some basic commands are:
```
sudo su
sudo apt-get update
sudo apt install docker.io
docker --version
sudo apt install git
git --version
docker pull nginx
docker ps -a
git clone https://github.com/Meghana4c4/project.git
ls
cd project
ls
cd ..
docker images
docker run -d -p80:80 nginx (changing ports Hostport:ContainerPort)
docker ps -a
docker exec -it [Contannier_ID] /bin/bash
ls
cd usr/share/nginx
rm -r html
ls
cd ..(3 times)
exit
docker cp /home/ubuntu/project 8196ce9dbcc0:/usr/share/nginx/html
```
Copy and Paste the Public IP in New page and check the page
