# docker-machine

```sh
$ docker-machine create --driver virtualbox node1
$ docker-machine create --help

$ docker-machine ls
$ docker-machine ssh node1
$ docker-machine env node1
$ eval $(docker-machine env node1)

$ docker-machine ip node1
$ docker-machine start node1
$ docker-machine stop node1
```

## Reference
- [docker machine drivers](https://docs.docker.com/machine/drivers/)
- [docker authz python plugin](https://etoews.github.io/blog/2016/07/30/develop-a-docker-authz-plugin-in-python/)
