# Spring Data Rest with multiple integration tests approaches


### How to use
*Gradle is required.*

To run: 
```
gradle bootRun
```

### Requests
- `GET http://localhost:8080/productBrands/search/findByName?name=type one`

### Local Jenkins
`docker run -p 8081:8080 -p 50000:50000 jenkins:alpine`
