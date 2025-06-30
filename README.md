# Ape Framework development stack

Ape Framework development stack using [Docker Compose](https://docs.docker.com/compose).

| Service | Docker URL  | Local URL                               |
| ------- | ----------- | --------------------------------------- |
| Node.js | `node:3000` | [localhost:3000](http://localhost:3000) |

Deploy stack:

```
docker compose up -d
```

## Development

Get a Node.js container shell:

```
docker compose exec node bash
```
