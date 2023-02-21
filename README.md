# CWF
docker run -d -it -p 420:80 --name=22051086_svr ubuntu:18.04 /bin/bash -c "apt-get update && apt-get install -y apache2"

docker commit 22051086_svr 22051086_webimage

docker run -d -it -p 42000:80 --name=S2_22051986_Server 22051086_webimages:latest /bin/sh -c  "/etc/init.d/apache2 start && tail -f /dev/null cmd"

docker rm -f 22051086_svr_test

docker rmi 22051086_webimages_test:latest 



docker run -d -it -p 35000:80 --name=S2_22051986_Server :latest /bin/bash -c "/etc/init.d/apache2 start && tail -f /dev/null cmd"
docker rmi web-app2 
