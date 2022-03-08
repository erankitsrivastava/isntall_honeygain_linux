# isntall honeygain on linux over docker

Type `uname -i` to get the hardware version

Download as per your hardware version: https://download.docker.com/linux/static/stable/

`wget https://download.docker.com/linux/static/stable/x86_64/docker-20.10.8.tgz`

`tar xzvf docker-20.10.8.tgz`

`sudo cp docker/* /usr/bin/`

`sudo dockerd &`

`sudo docker pull honeygain/honeygain`

`sudo docker run honeygain/honeygain -tou-get`

`docker run honeygain/honeygain -tou-accept -email ACCOUNT_EMAIL -pass ACCOUNT_PASSWORD -device DEVICE_NAME`
