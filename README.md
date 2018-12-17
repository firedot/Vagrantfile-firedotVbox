# Vagrantfile-firedotVbox
Vagrantfile for the firedot/xenial64 box. 

1. Download and install Oracle VirtualBox from [here](https://www.virtualbox.org/wiki/Downloads) 
2. Download and install Vagrant from [here](https://www.vagrantup.com/downloads.html)

# How to use this repository

- Clone the repository

```
git clone https://github.com/firedot/Vagrantfile-firedotVbox.git
```
or by downloading it as a ZIP file from the link: 

```
https://github.com/firedot/Vagrantfile-firedotVbox/archive/master.zip
```
- Go to the cloned repo directory

```
cd Vagrantfile-firedotVbox
```
- Run the following command to spin-up your virtual machine
````
vagrant up
````
- You could check the status of the Vagrant box: 
````
vagrant status
````
- You could connect remotely to the box you just brought up with: 
````
vagrant ssh
````

- To destroy the VM created from your Vagrantfile, run the following command:

```
vagrant destroy
```

- Additionally you could find some useful vagrant commands [here](https://www.vagrantup.com/docs/cli/) 
