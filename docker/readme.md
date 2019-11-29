docker cotainer 

flags : 

 --detach : run this container in the background
 
 --publish 8080:80 : 
 
 publishs port 80 in the container (the default port for nginx) via port 8080 on our host
 this flag is a feature that allows us to expose networking through the container onto the host.
 
 --name [sample name]  : names the container . every container has a name, if you don't spcify one, Docker will randomly assign one for you
 
 
