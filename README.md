# BasicNodeNginxPlaybook

Quick setup guide. For more details on the functionality visit https://takeondevops.com

1. Clone this repository to your master node

2. Edit the inventory file and set relavent details as per your choice. You can then change the host setting in the playbook if required.

3. Open the variables directory and set the ansible manged node username and password in the credentials directory

4. Optional: Disable stricthostkey checking from the master node if required. Or simply ensure that you have connected via SSH at least once to you managed node.

5. Run the script. Example: Ansible-Playbook playbook.yml

6. Additional step: Encrypt the password file with ansible vault as required. I have left as is because it is for a demo
