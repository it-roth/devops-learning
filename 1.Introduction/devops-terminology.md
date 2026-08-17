## NOTE

Requirement 
1. VsCode
2. VirtualBox -> ubuntu
```bash
which virtualbox
```
3. Vagrant
```bash
vagrant version


# macos
# box = os
vagrant init <box-name>
vagrant init bento/ubuntu-24.04

# to turn on the machine
# first try -> it will download the iamge from cloud
vagrant up
vagrant status
vagrant ssh # remote to the VM (using ssh)
vagrant ssh-config


# inside your vm machine 
sudo apt update && sudo apt upgrade -y
sudo apt install neofetch -y


vagrant halt # turn off
vagrant destroy # delete the machine inside virtualbox

# after changing the configuration inside VagrantFile
vagrant reload
vagrant reload --provision
#ssh user@ip

#window / ubuntu
vagrant init ubuntu/jammy64
```  






### Reviews
- Keyword in devops
- Prepare enviroment for testing / learning server (ubuntu)
- Setup enviroment
    - vagrant (virtual env)
    - virtualbox / vmware
- vagrant 
    - find the lightweight vm box (os)
    file `Vagrantfile`
    - testing / validation tasks before putting in on production1
    - ex. kafka cluster
