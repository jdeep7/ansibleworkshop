# ansibleworkshop
Automating the deployment a Flask app onto a webbservers and load balancing using Ansible.
1) Created a network, ssh key, and, a server with a floating ip to try and connect to it.
2) Changed rules of security group to accept tcp requests from all ip adress and on port22.
3) Later created remaining dev servers and HAproxy server using the ssh key previously generated.
4) Then wrote an ssh config file to mitigate the password entry and used bastionNSO as the jumphost to reach other servers.
5) Installed ansible on host machine.
6) Created a hosts file for ansible to use in playbook to communicate and manage the server groups.
7) Started site.yaml and worked my way through each step.

