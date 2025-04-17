 Installation of Ansible in Ubuntu
Run this command in the ansible Master machine

sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible

Make sure we have python installed in all the machines

I have used 3 ec2 instances for performing this experiment

Once ansible is installed in Master node

Go to 
/et /ansible/ hosts

Now paste the ip address of the slaves

slave1 ansible_ hosts=private ip of the slave

Now to make a connection between them follow the ansible document
