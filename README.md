# simple-nginx

Simple nginx web server to show very very simple plain HTML page

## How to use

Pull from [DockerHub](https://hub.docker.com/)

```bash
docker pull fatahnuram/simple-nginx
```

Deploy to your needs

```bash
docker run --detach --name simple-nginx -p 8080:80 fatahnuram/simple-nginx
```

Access your deployed `simple-nginx`

```bash
curl 127.0.0.1:8080
```

## How to stop

Stop running container

```bash
docker stop simple-nginx
```

Remove that stopped container

```bash
docker rm simple-nginx
```
