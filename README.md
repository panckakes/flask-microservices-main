# Car Navigation
  
  
  
# Introduction
Car.os is a custom navigatgion system built for my personal car to introduce features that exist in new cars (and not).  The system utilizes raspberry pis 
and a 7" touch screen that will integrate into a double-din enclosure to replace the current radio head unit.  

Main featues of this project include:

  - Navigation
  - Music player
  - car telementry via OBD2
  - position telementry via Navio2

# Quick Start

If you want to run this on your local system for testing.  CD into the root of the main folder where docker-compose.yml is located 

Before launching 2 dependices are required
* [Docker](https://www.docker.com/) - Software containerization software
* [node.js] - evented I/O for the backend

Once installed you may run these commands

```sh
$ cd flask-microservices-main
$ docker-compose up --build
```

The server should be running on 127.0.0.0:9000

# Tech Stack
![Tech map](https://i.imgur.com/wJu9tdM.png)

