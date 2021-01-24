# ansible_demo
This is a trial project to explore ansible basics.

* Create two AWS ec2 instances with AMI Ubuntu Server 18.04
* One ec2 instance serves as a "controller" and another one as a "managed node" under the controller.
## Steps for Controller setup 
1. Install Python

    `sudo apt install python-minimal`	
2. Create a key pair for SSH login into the managed nodes.
   
    `ssh-keygen`
3. Copy SSH key-pair to the "managed node" using  
    
    `ssh-copy-id`
4. Update ubuntu repository 
    
    `sudo apt-get update`
5. Install ansible 

    `sudo apt-get install ansible -y`

6. check ansible version 

    `ansible --version`
