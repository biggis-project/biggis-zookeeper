# BigGIS Zookeeper
[![Build Status](https://travis-ci.org/biggis-project/biggis-zookeeper.svg?branch=master)][Travis]
[Travis]: https://travis-ci.org/biggis-project/biggis-zookeeper
Docker container for Apache Zookeeper

## Prerequisites
Docker Compose >= 1.9.0

## Deployment
```sh
docker-compose up -d
```

## Ports
- Zookeeper is running on port `2181`
- Replicated Zookeeper ports `2888` and `3888` (not mapped to host)
