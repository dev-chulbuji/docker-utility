# docker auth plugin

```sh
$ echo '{ "Name": "nodejs-authz-example","Addr": "http://localhost:9000/"}' > auth-plugin.json
$ mkdir -p /etc/docker/plugins 
$ mv auth-plugin.json /etc/docker/plugins

```
