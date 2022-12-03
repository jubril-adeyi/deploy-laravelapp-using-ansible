# Ansible roles to set up Apache, Php, composer, ufw, mysql and SSL to securely deploy the laravel application on a remote server
This code is tested on an AWS Ubuntu machine

# Requirements
<ul> 
<li>An EC2 Ubuntu Instance (Anisble Server) - EC2 Ubuntu Instance (Ansible should be installed) which will serve as the master </li>
<li> Another target EC2 Instance, where the packages and deployment will be automated remotely.</li>
<li>All variables are declared under ansible/vars/</li>
</ul>

# Prerequisite


<ul> 
<li> Update inventory file /ansible/hosts </li>
<li> Generate the public key for the user ubuntu ssh-keygen on Ansible Server.</li>
<li>Copy the id_rsa.pub from cd ~./ssh and paste it on the target Server vi ~/.ssh/authorized_keys </li>
</ul> 

# Access the application 

Make sure security group of AWS EC2 target Server is open for port 80 (HTTP) and 443 (HTTPS)

