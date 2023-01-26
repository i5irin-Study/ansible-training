# Ansible Training

Requirements

```
sudo apt-get update
sudo apt-get install -y openssh-server
sudo sed -i "s/^#Port 22/Port 22/g" /etc/ssh/sshd_config
ssh-keygen -t rsa
cp ~/.ssh/id_rsa.pub ~/.ssh/authorized_keys
sudo service ssh start
```
