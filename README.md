# aerospike-ce-docker-compose
🚢 Docker Compose recipe for Aerospike Database Community Edition

## Aerospike start-up

```console
> docker-compose up
```

## Usage

```console
> docker run -ti aerospike/aerospike-tools:latest aql -h  $(docker inspect -f '{{.NetworkSettings.IPAddress }}' aerospike)

> docker run --platform linux/amd64 -ti aerospike/aerospike-tools:latest aql
```

## License

[MIT](LICENSE)