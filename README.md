# ansible_demo
This is trial project to explore ansible basics
Create two aws ec2 instances with AMI Ubuntu Server 18.04
One ec2 instance serves as a "controller" and another one a "managed node" under the controller
Controller setup 
Install Python 
sudo apt install python-minimal	
Use ssh-keygen to create a key pair for SSH login to the managed nodes
Copy SSH keys to the "managed node" using  ssh-copy-id 
Update ubuntu repository sudo apt-get update
Install ansible sudo apt-get install ansible -y
check ansible version ansible --version
