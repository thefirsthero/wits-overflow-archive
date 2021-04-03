# wits_overflow

This is the client application for the Wits Software Design project 2021.

#### Getting started

For a description on how to get up and running, see the wiki article:
[https://github.com/gltch/wits-overflow/wiki/Getting-Started](https://github.com/gltch/wits-overflow/wiki/Getting-Started)

#### Flutter commands:

- Check that Flutter is installed correctly

    ``flutter doctor``

- Run tests:

    ``flutter test``
    
- Build the website: 

    ``flutter build web``

- Build android apk:

    ``flutter build apk --split-per-abi``

#### Docker commands:

- Create the docker image: 

    ``docker build -t wits-overflow:v0.0.1 .``

- Create and run the docker container: 

    ``docker run --name wits-overflow -e PORT=80 -d -p 5555:80 wits-overflow:v0.0.1``