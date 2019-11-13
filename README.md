# DockerHelloWorld
Run C with Docker

1. Created a folder to make a "DockerFile"
$ touch Dockerfile // Dockerfile is the example name for the Dockerfile

2. Also create a c file to print "Hello, World" in the same directory

3. Created two imgaes. One for ubuntu and another one for gcc
$ docker pull ubuntu:18.04 
$ docker pull gcc

4. Pulling those images into Dockerfile and run the C file 
& nano Dockerfile // to modify the Dockerfile, control+x to EXIT

5. Create an image with a dockerfile 
$ docker build -t helloworld_c . // make sure you are in the right directory

6. Run...
$ docker run -it helloworld_c


