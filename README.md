# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.6.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.6.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.6.5/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides

The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

# create docker image

```
docker build -t spring-boot-docker.jar .
```

# check docker images

```
    docker image ls
```

# Run docker image

```
docker run -p 9090:8080 spring-boot-docker.jar
```
# Docker HUB
```
    Docker HUB is like a repository same as git repository where we will store docker image. 
        Tag Image
    docker tag <image-name> <docker-id>/<image-name>
        Push image to Docker HUB
        It might take some time will pull image from docker and will push to docker hub
    docker push <docker-id>/<image-name>
    docker pull <docker-id>/<image-name>
```
