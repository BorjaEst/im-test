# IM Online Dashboard
Online dashboard with simplified interface for deploying virtual machines and other services.

## Link: [IM Dashboard](https://appsgrycap.i3m.upv.es:31443/im-dashboard/login)

>https://appsgrycap.i3m.upv.es:31443/im-dashboard/login


## Usage

Go to the link indicated bellow and login with [OIDC](https://aai.egi.eu/oidc/) following the instructions and your institution credentials:
![IM_Welcome][IM_Welcome]

After you have logged in, you should choose the service you would like to deploy. In Synergy we will mainly use "Virtual machines":
![New_VM][New_VM]

In the next page, you can indicate the resources your service would need. After you are done, click on "Site Selection" **(Submit is not enabled yet)**:
![VM_Specs][VM_Specs]

In this page context, you can indicate the location where your instance will be deployed. After you are done, now you can click on **Submit**:
![VM_Site][VM_Site]
> Note that all sites and images might take some seconds to load. Try to click again on the menu. 

Now your virtual machine will go to the status of **"running"**. It means it is on its configuration process. Wait until the status is green and says **"configured"**:
![Creating][Creating]

Once your machine is **"configured"** it is ready to be used. Click on the "VMs" column to access to the instance details:
![Configured][Configured]

In this page, following the menu on the arror 1, you can manage the status of your Virtual Machine (and also access to the log file if you need support). To **access** your virtual machine, you have to download the private key using the button indicated by the arrow 2. 
![VM_Details][VM_Details]
> After pressing the **"Download"** button, a "key.pem" file will be downloaded. This is your ssh private key and must be stored in a safe place.

And that is all! To access the VM you have to use [ssh](https://www.ssh.com/ssh/key/). You can find easy isntructions about how to access with your downloaded private "key.pem" in this link:

## [SHH access instructions](): 


[IM_Welcome]:   ./images/Welcome.jpg
[New_VM]:       ./images/New_VM.jpg
[VM_Specs]:     ./images/VM_Specs.jpg
[VM_Site]:      ./images/VM_Site.jpg
[Creating]:     ./images/Creating.jpg
[Configured]:   ./images/Configured.jpg
[VM_Details]:   ./images/VM_Details.jpg