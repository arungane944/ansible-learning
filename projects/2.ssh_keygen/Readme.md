ssh-keygen

ssh-copy-id -i ansible-demo.pub ubuntu@3.83.166.29


ssh-keygen
Generating public/private ed25519 key pair.
Enter file in which to save the key (/Users/arun/.ssh/id_ed25519): /Users/arun/Documents/GitHub/learn-ansible-basics-beginners-course/projects/2.ssh_keygen/ansible-demo
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/arun/Documents/GitHub/learn-ansible-basics-beginners-course/projects/2.ssh_keygen/ansible-demo
Your public key has been saved in /Users/arun/Documents/GitHub/learn-ansible-basics-beginners-course/projects/2.ssh_keygen/ansible-demo.pub
The key fingerprint is:
SHA256:MU1c1rO0OpHFnQ49OZH8e/gXc7RoExfnm+gFFeiR0TI arun@Aruns-MacBook-Air.local
The key's randomart image is:
+--[ED25519 256]--+
|         ...o+B+*|
|         o.. E*%o|
|        o . .+B=*|
|         o  o+oo+|
|        S    o*o=|
|            o=.Oo|
|            o.o.=|
|             .  o|
|                .|
+----[SHA256]-----+



ssh-copy-id -i ansible-demo.pub ubuntu@3.83.166.29 
/usr/bin/ssh-copy-id: INFO: Source of key(s) to be installed: "ansible-demo.pub"
The authenticity of host '3.83.166.29 (3.83.166.29)' can't be established.
ED25519 key fingerprint is SHA256:cKmXjebWcL6Gh5CsM+bLrxx7nT32PFO5dk/i9HvZApI.
This host key is known by the following other names/addresses:
    ~/.ssh/known_hosts:47: ec2-3-83-166-29.compute-1.amazonaws.com
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
/usr/bin/ssh-copy-id: INFO: attempting to log in with the new key(s), to filter out any that are already installed
/usr/bin/ssh-copy-id: INFO: 1 key(s) remain to be installed -- if you are prompted now it is to install the new keys
ubuntu@3.83.166.29: Permission denied (publickey).