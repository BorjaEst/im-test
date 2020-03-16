# im-test
Test the applications of Infrastructure Manager with TOSCA templates

## Dependencies
* [docker](https://www.docker.com/)
* [docker-compose](https://docs.docker.com/compose/)

> I recommend to add your user to docker group to avoid calling sudo always:
> [Post-installation steps for Linux](https://docs.docker.com/install/linux/linux-postinstall)

## Usage
Just run:
```sh
$ docker-compose up --build
```

### im-web
With your browser go to [http://localhost/im-web/](http://localhost/im-web/).


### alien4cloud
With your browser go to [http://localhost:8088/#/](http://localhost:8088/#/)
* User: admin
* Pass: admin
> Local instance.




# Notes

>It looks that the export feature will be available in the next release. 
>[a4c - TOSCA](https://alien4cloud.github.io/#/documentation/2.1.0/concepts/tosca.html)
