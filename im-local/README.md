# IM Local with Web interface
Deploys a local instance of im and im-web

## Dependencies
* [docker](https://www.docker.com/)
* [docker-compose](https://docs.docker.com/compose/)

> I recommend to add your user to docker group to avoid calling sudo always:
> [Post-installation steps for Linux](https://docs.docker.com/install/linux/linux-postinstall)


## Usage: 
Just run:
```sh
$ docker-compose -f "im/docker-compose.yml" up -d --build
```
Stop with:
```sh
$ docker-compose -f "im/docker-compose.yml" down
```
