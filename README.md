# Spring Boot Demo

`docker build -t spring-boot-demo .`

`docker run -p 8080:8080 spring-boot-demo`

`curl http://localhost:8080/api/hello`

[Swagger](http://localhost:8080/swagger-ui/index.html)

http://localhost:8080/v3/api-docs

mvn org.springdoc:springdoc-openapi-maven-plugin:1.6.0:generate -Dspringdoc.outputFileName=openapi.json -Dspringdoc.outputDir=./target -Dspringdoc.apiDocsUrl=http://localhost:8080/v3/api-docs
