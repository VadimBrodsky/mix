```shell
docker network create --driver=overlay web
```

Pass a environment variable into a stack file:

```shell
env HOST=test.local docker stack deploy -c proxy.yml proxy
```
