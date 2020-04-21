# Traefik

[Traefik](https://traefik.io/) is a reverse proxy / load balancer container used to route the containers trafic.
You must initialize this container to be able to route the trafic of your containers.

Current used version is the **1.7.14**

You can check the containers that are routed via the Traefik application by going to http://127.0.0.1:8081/dashboard/

## Start the container

```bash
make start
```

## Stop the container

```bash
make stop
```

