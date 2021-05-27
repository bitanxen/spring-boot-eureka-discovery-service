# spring-boot-eureka-discovery-service
spring-boot-eureka-discovery-service

# Build Application

```
mvnw clean install -DskipTest (for Windows)
./mvnw clean install -DskipTest (for Linux)
```

# Build Image

```
docker build -t bitanxen/eureka-discovery-service .
```

# Push Image

```
docker push bitanxen/eureka-discovery-service
```