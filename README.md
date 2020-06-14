# Open-Vidu-Node
This is a Video Call sample project used [OpenVidu] Server as core and written with Node.js (Express).


## Prerequisites
Make sure you have these installed in your system:
git, nvm, npm, nodemon, docker, docker-compose


## How to use
First go to docker folder and use `.env.example` to create `.env` file for docker-compose file configuration. Then run:

```
sudo docker-compose up --build
```

Then go back to main folder and create `.env` file using `.env.example`. After that run:

```
npm i
```

then:

```
nodemon
```

### References
[OpenVidu]: https://docs.openvidu.io/en/2.14.0/