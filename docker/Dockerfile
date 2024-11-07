FROM ubuntu:latest

#set working dir in the image
WORKDIR /app

#copy files from host file system to image file system
COPY . /app

#Install packages
RUN apt-get update && apt-get install -y python3 python3-pip

#set env variables
ENV NAME world

#Run command to start the application
CMD ["python3", "hello.py"]
