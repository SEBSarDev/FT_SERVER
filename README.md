# FT_SERVER
An introduction to docker.

This project allow me to learn some basics element of docker. 
We had to create an environment with nginx, mariaDB and wordpress in order to allow wordpress to run inside the container, and be persistant.

To launch container :
```
$ sudo docker build .
...
...
...
Successfully built 317570de6cb6
$ sudo docker run ID_CONTAINER_BUILD (here 317570de6cb6)
```

