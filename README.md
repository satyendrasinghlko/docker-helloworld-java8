# Docker Java 8 helloworld

Requires:
* [Docker](https://www.docker.com/)
* [Boot2Docker](http://boot2docker.io/)
* JDK (to compile java file locally)

To run:

```
# compile class
javac helloworld.java

# build image
docker build -t java8-helloworld .

# run image
docker run -it --rm --name my-running-app java8-helloworld
```
