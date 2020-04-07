# im-test
Test the applications of Infrastructure Manager with TOSCA templates.

## Dependencies
* [docker](https://www.docker.com/)
* [docker-compose](https://docs.docker.com/compose/)

> I recommend to add your user to docker group to avoid calling sudo always:
> [Post-installation steps for Linux](https://docs.docker.com/install/linux/linux-postinstall)

## Running IM in local 

Just run:
```sh
$ docker-compose -f "im/docker-compose.yml" up -d --build
```
Stop with:
```sh
$ docker-compose -f "im/docker-compose.yml" down
```

Wait a minute (more or less) and with your browser go to [http://localhost/im-web](http://localhost/im-web)
* User: admin
* Pass: admin
> Local instance.


# Running IM in the EOSC service 
1. Watch [Infrastructure Manager Demo on EGI FedCloud](https://www.youtube.com/watch?v=barnku5AsBA&list=PLgPH186Qwh_37AMhEruhVKZSfoYpHkrUp&index=5).
2. Login into the [IM service](https://appsgrycap.i3m.upv.es:31443/im-web/index.php) with your EGI credentials.
3. Go to Credentials and add a source (Button Add+); Select type "EGI" and introduce  selecting your VO and Site. After that "Save".
4. Create a topology in "Topologies > Add +". You can use one of the templates located in "im-web > tosca" then clic on "Save".
5. To lunch in the instance on the endpoint, on the page "Topologies" click on the launch icon.
6. You will see your instance is beeing created.


Images!!!



## Issues



## Optional
- README.md inside a4c-deep folder for a GUI to generate tosca templates 

