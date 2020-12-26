# Playbook-for-WebServer-on-Docker
This Ansible Playbook is used to configure a Docker Container hosting WebPages.
<h2>Inventory File for Ansible</h2>
<p>The file named config.txt is the Ansible Inventory file. Copy that file to your Linux Machine and make necessary changes to the IP address of the Managed Node, username , password and the prefferable connection to use.</p>
<h2>Config File for Ansible</h2>
<p>The file ansible.cfg file has to be copied to the /etc/ansible/ directory. Here put the location of the Inventory file previously copied.</p>
<h2>Ansible Playbook</h2>
<p>To run the Ansible Playbook just copy the code to the Linux Machine. Now instead of the ISO file you can directly configure EPEL Release on the Linux Machine.</p>
