# Prometheus IOTA Node Exporter

## Summary

This Docker Compose will export the IOTA IRI node information and
machine information.

## Prerequisites

1. Install the docker

2. To setup your node information, use the environment example `.env.example`

```
  $ cp .env.example .env
```

## Run Docker Compose

To run the Docker Compose, execute the following command:

```
  $ docker-compose up -d
```

## Publish to Docker Hub

To stop the Docker Compose, execute the following command:

```
  $ docker-compose down
```