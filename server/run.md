### Gradle Run
```sh
gradle build
gradle bootRun
```

### Spring Port Define
* Set ``` server.port ``` as system property using command line option to jvm ``` --server.port=8090 ```
```sh
java -jar spring-app.jar --server.port=8090
```
* Or add application.properties in ``` /src/main/resources/ ``` with
```sh
server.port = 8090
server.port = 0 [For random port use]
```
