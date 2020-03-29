Sample nodejs application with docker Conatiner
Installation
    // clone the application with git clone

    // then install the npm modules using
     
    npm install
Running the application
    node server.js
Building docker image
    docker build -t <imagename:version> .
Running docker container
    // 9005 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9005 <imagename:version>
