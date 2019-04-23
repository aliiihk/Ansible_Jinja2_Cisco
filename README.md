# Creating Basic Configurations in Ansible using Jinja2 Templates for 

A Playbook and Jinja2 file is used to create the below specified configurations:
  - Set the hostname to R1, R2, R3 and R4 respectively
  -	Set the login credentials to cisco/cisco
  -	Set the priviledges exec password to class
  -	Create Interface loopback0 on all routers with IP of 1.1.1.1/32 on R1, 2.2.2.2/32 on R2, and so on
  -	Create Interface Vlan X (x being the Router number) – with ip address of 11.11.11.11/24 on R1, 22.22.22.22/24 on R2 and so on
  -	Ensure plain-text passwords are encrypted automatically
