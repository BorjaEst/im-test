# SSH Access to IM deployments 
Instructions/Example of how to access to the resources using ssh.


## Installation
By default OpenSSH ships with most of linux distributions. However in case it is not istalled, it can be solved easyly by running:
```sh
$ sudo apt update
$ sudo apt install openssh-client
```


## Usage
The first step is to obtain the IP and user and key for the endpoint. For example thorught the IM Dashboard this information is on the "vminfo" page:

![IP_User_key](./images/IP_User_key.jpg)

Then run the following command:
```sh
$ ssh -i key.pem <user>@<ip-address>
```

### TODO: Fingerprint check???

If the user and key are correct you will be logged inside the virtual machine.

