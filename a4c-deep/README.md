# a4c
Application to build and deploy TOSCA templates.
In this mrepository is used as option to generate Tosca templates.

## Dependencies
* [docker](https://www.docker.com/)
* [docker-compose](https://docs.docker.com/compose/)

> I recommend to add your user to docker group to avoid calling sudo always:
> [Post-installation steps for Linux](https://docs.docker.com/install/linux/linux-postinstall)

## Start and stop
To start:
```sh
$ docker-compose -f "a4c-deep/docker-compose.yml" up -d --build
```
Stop with:
```sh
$ docker-compose -f "a4c-deep/docker-compose.yml" down
```

Wait a minute (more or less) and with your browser go to [http://localhost:8080/#/](http://localhost:8080/)
* User: admin
* Pass: admin
> Local instance.


# Notes

> https://alien4cloud.github.io/#/documentation/2.2.0/concepts/tosca.html

> https://a4c.ncg.ingrid.pt/#/

> https://github.com/indigo-dc/alien4cloud-deep/blob/master/README.md

> https://github.com/indigo-dc/alien4cloud-deep/blob/master/README.md

> https://github.com/indigo-dc/tosca-templates

> https://github.com/indigo-dc/tosca-templates/blob/master/simple-node.yml

> Extensive info on TOSCA templates:
> - http://docs.oasis-open.org/tosca/TOSCA-Simple-Profile-YAML/v1.0/csd03/TOSCA-Simple-Profile-YAML-v1.0-csd03.html

