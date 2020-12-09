# RYU-Docker
The RYU controller pre-installed to be used as an image file for Docker.

Execute the following commands in Windows CMD running Docker Desktop:

docker import C:\users\Billy\Desktop\RYU.tar ryu

docker run -it -p 8181:8181 -p 8101:8101 -p 9876:9876 -p 6653:6653 -p 6640:6640 --entrypoint "/bin/bash" ryu
