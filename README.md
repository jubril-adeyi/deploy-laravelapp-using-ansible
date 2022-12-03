# Ansible roles to set up Apache, Php, composer, ufw, mysql and SSL to securely deploy the laravel application on a remote server
This code is tested on an AWS Ubuntu machine

# Requirements
<ul> 
<li>An EC2 Ubuntu Instance (Anisble Server) - EC2 Ubuntu Instance (Ansible should be installed) which will serve as the master </li>
<li> Another EC2 Instance, where the packages and deploymnt will be automated remotely.</li>
<li>All variables are declared under ansible/vars/</li>
</ul>
