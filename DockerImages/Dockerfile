# Run gameroom.c

#Download base image ubuntu 18.04
#FROM: Define the base image and start the build process
FROM ubuntu:18.04
FROM gcc
# Which is under the Dockerimages file
WORKDIR /usr/src/
COPY . /usr/src/

#Update Ubuntu Software repository
RUN apt-get update
   # rm -rf /var/lib/apt/lists/*

#RUN gcc ./helloWorld.c -o helloDocker

RUN gcc -o helloworld ./helloWorld.c -pthread
CMD ["./helloworld"]
