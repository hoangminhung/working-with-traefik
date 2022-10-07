Before run this docker compose. You have to create a docker network for this.
```
docker network create --ip-range=192.168.200.0/24 --gateway=192.168.200.1 --subnet=192.168.200.0/24 --driver=bridge network-test
```
