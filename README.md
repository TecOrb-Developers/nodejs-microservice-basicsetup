

## Requirements

* [MongoDB](https://www.mongodb.com/download-center "MongoDB")
* [NodeJS](https://nodejs.org/en/download "NodeJS")

## Build for local development

You have to use the following command to start a development server:

```sh
npm run dev
```

See `package.json` for more details.

## Build for staging and production environments

Use following command to build project:

```sh
npm run build
```

Use following command to start project on staging and production environments:

```sh
npm start
```

See `package.json` for more details.

## Tests

Following tests libraries are used for unit/integration tests:
* [MochaJS](https://mochajs.org "MochaJS")
* [SinonJS](http://sinonjs.org "SinonJS")
* [ChaiJS](http://chaijs.com/ "ChaiJS")

Tests are kept next to source with following pattern *.spec.js

Use following command to run tests:

```sh
npm test
```

Use following command to run tests coverage:

```sh
npm run coverage
```

## Docker container

There is available Docker container and Docker Composer if you would like to run many NodeJS Microservices.

Build API Microservice by using following command:

```sh
npm run build
```

Then use following command to build Docker containers:

```sh
docker-compose up -d --build
```

See `Dockerfile` and `docker-compose.yml` for more details.
