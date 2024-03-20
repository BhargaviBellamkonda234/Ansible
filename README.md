# Ansible

sudo apt install ansible

ansible --version

### prerequisite is to have password less authentication
ssh into Ec2 servers and do ssh-keygen
go into authorised keys file and add public key of ansible server to authorised keys file of the target server

### adhoc commands
ansible -i inventory all -m "shell" -a "touch devopsclass"
