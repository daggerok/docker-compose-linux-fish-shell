# docker-compose-linux-fish-shell
install docker-compose on linux with fish shell

fish:

```fish
set DOCKER_COMPOSE_VERSION 1.9.0
curl -L https://github.com/docker/compose/releases/download/$DOCKER_COMPOSE_VERSION/docker-compose-(uname -s)-(uname -m) > docker-compose
chmod +x docker-compose
sudo mv -f docker-compose /usr/local/bin/
```

bash:

```bash
export DOCKER_COMPOSE_VERSION=1.9.0
curl -L https://github.com/docker/compose/releases/download/$DOCKER_COMPOSE_VERSION/docker-compose-$(uname -s)-$(uname -m) > docker-compose
chmod +x docker-compose
sudo mv -f docker-compose /usr/local/bin/
```
