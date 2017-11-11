#Spring Boot Admin Docker [![Codefresh build status]( https://g.codefresh.io/api/badges/build?repoOwner=gexadaktilos&repoName=spring-boot-admin&branch=master&pipelineName=spring-boot-admin&accountName=gexadaktilos&key=eyJhbGciOiJIUzI1NiJ9.NWEwMzY5MDM2MzQ0ZjEwMDAxOWE4ZmMz.WGv9EAwIBVknuNHaDOTIPFeJlAOwN2AOw7OY4N1YtbU&type=cf-1)]( https://g.codefresh.io/repositories/gexadaktilos/spring-boot-admin/builds?filter=trigger:build;branch:master;service:5a061fb7c921d400014ffc02~spring-boot-admin)

Docker image is publicly available as [geeksada/spring-boot-admin](https://hub.docker.com/r/geeksada/spring-boot-admin/).

You can run spring-boot-admin in Docker with this command:
```sh
docker run -d -p 8090:8080 --name spring-boot-admin geeksada/spring-boot-admin:1.5.4
```
Go to http://localhost:8090 (or http://docker-host:8090) on your browser.


