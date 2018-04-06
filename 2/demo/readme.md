SETCON 18
=========

build app
---------
Linux:

    ./gradlew build

Windows:

    gradlew build

build docker image
------------------
    docker build -t setcon18-java .

run docker image
----------------
    docker run --rm --name setcon18test -p 8090:8080 setcon18-java

and open in browser http://localhost:8090/

stop docker image
-----------------
    docker stop setcon18test
