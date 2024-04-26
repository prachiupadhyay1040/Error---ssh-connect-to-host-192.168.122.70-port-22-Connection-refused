# unable-to-ssh
ssh: connect to host 192.168.122.70 port 22: Connection refused


### Solution:
#### 1. Make sure the system us up-to-date Before installing OpenSSH:

sudo apt update && sudo apt upgrade -y

#### 2.Enter the following command to install OpenSSH:

sudo apt install openssh-server openssh-client

#### 3. Now start the server:

sudo systemctl enable ssh

#### 4. Check the status of the newly installed server:

sudo systemctl status ssh

##### Now you are Able to take ssh.
