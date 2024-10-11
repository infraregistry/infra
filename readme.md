# infraregistry IaC

## Services

- PostgreSQL + TimescaleDB Extension
- RabbitMQ
- SurrealDB

## Running Locally

```sh
docker compose up -d
```

> Check out [Surrealist](https://github.com/surrealdb/surrealist) to connect to SurrealDB visually to manage and test the graph.

## Deploying

To deploy the manifests to the cluster, run:

```sh
kubectl apply -f manifests
```
