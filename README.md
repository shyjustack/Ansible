# Ansible
Step 1 — Installing Ansible
```
sudo apt-add-repository ppa:ansible/ansible
```
```
sudo apt update
```
```
sudo apt install ansible
```
add the server details 
/etc/ansible/hosts

ansible-inventory --list -y

create the ssh key in the server 
ssh-keygen

copy the key to all the client 
ssh-copy-id -i ~/.ssh/id_rsa.pub root@192.168.0.104

ansible -m ping Client or ip 
