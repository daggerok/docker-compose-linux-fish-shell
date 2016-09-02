# docker-compose-linux-fish-shell
install docker-compose on linux with fish shell

```fish
cd /tmp
curl -L https://github.com/docker/compose/releases/download/1.8.0/docker-compose-(uname -s)-(uname -m) > ./docker-compose
chmod +x ./docker-compose
sudo mv -d ./docker-compose /usr/local/bin/
```
