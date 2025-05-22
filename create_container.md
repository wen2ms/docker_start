- **View all images**

    `docker images`

    `docker image ls`

- **Remove the container**

    `docker rm my_ubuntu_container` 

- **Map port 10000 inside the container to 10000 on host and mount a folder**

    `docker run -p 8000:10000 -v /home/user/web_files:/var/www --name my_ubuntu_container ubuntu`

- **Docker cp**

    `docker cp ~/file my_container:/root/file`