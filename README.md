# dice-api

A simple example API in compojure-api, created for the wiki tutorial.

## Usage

### Run the application locally

`lein ring server`

### Packaging and running as standalone jar

```
lein do clean, ring uberjar
java -jar target/server.jar
```

### Packaging as war

`lein ring uberwar`

## License

Copyright © Annaia Berry
Licensed with the EPL-1.0
