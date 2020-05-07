# IM Command Line Interface 

## Installation:
1. Read documentation at [imdocs.readthedocs](https://imdocs.readthedocs.io/en/latest/client.html).
2. Install/ensure python and pip on your computer.
```sh
sudo apt install python3 python3-pip
pip3 install IM-client
```
3. Create the config file [.im_client.cfg](./im_client.cfg) in your home directory. Note that "localhost" should be replaced by the ip/name where the IM service is running.
4. Note the .im_client.cfg referes a file an ".auth.dat" you shoudl create this file also in the home directory. See [auth.dat.template](./auth.dat.template) for an example of this configuration file.

## Usage: 
1. Run the [docker-compose](../README.md) file and wait a minute (more or less).
2. Check you can connect to the IM running:
```sh
$ im_client.py list
Connected with: http://<defined-host-inim_client.cfg>:8800
No Infrastructures.
```
3. Try to deploy a simple instance (in AWS for example) using the RADL template [aws-radl-basic](aws-radl-basic) and the command line: 
```sh
$ im_client.py create aws-radl-basic 
Connected with: http://eoan-dev:8800
Infrastructure successfully created with ID: 812bcb60-8f9c-11ea-8616-0242ac110002
```
4. Deploy your custom infrastructure using TOSCA. You can use the templates from [tosca](../../tosca/README.md). To deploy use the following code:
```sh
$ im_client.py create <template-file-location>

```


