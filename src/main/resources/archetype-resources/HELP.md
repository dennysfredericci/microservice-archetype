# Guide to understand your new project

### Extra configuration needed 

Add a new server on your settings.xml

<server>
    <id>docker.io</id>
    <username>${docker.hub.user}</username>
    <password>${docker.password}</password>
</server>


# How to build

```
mvn clean install 

```


# Build and Deploy your Docker Image


```
mvn clean install dockerfile:push -Ddocker.user=${dockerHubUser}  -Ddocker.password=YOUR_PASSWORD
```

# Running your docker image

```
docker run --rm -p 8080:8080 ${dockerHubUser}/${artifactId}
```