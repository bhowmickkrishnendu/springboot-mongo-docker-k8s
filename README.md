Spring Boot Using Spring Data MongoDB Example

# Build Project Using Maven

Maven is java based build tool to build executable 

packages(jar, ear,war) for java based projects.

```bash
mvn clean package
```

## Create Docker Image
Docker is a continerization tool.

Create docker image using Dockerfile


```docker
docker build -t <RepoName>/spring-boot-mongo .
```

## List Docker Containers
```docker
docker ps -a
```

