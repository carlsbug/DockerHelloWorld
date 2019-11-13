#Download base image ubuntu 18.04
#FROM: Define the base image used to start the build process
FROM ubuntu:18.04 
FROM gcc
WORKDIR /usr/src/
COPY . /usr/src/

#Update Ubuntu Software repository
RUN apt-get update
   # rm -rf /var/lib/apt/lists/*
#Install GCC

RUN gcc ./helloWorld.c -o helloDocker
CMD ["./helloDocker"]

