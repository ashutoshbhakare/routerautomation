# Ansible Network Automation
Learn Router Automation with RH294
# Contents 
# CISCO IOS 
 	Configuring Router
	Introduction to CISCO IOS
	Basic IOS commands 
enable
configure t
show 
copy running-config startup-config
Setting IP Address
Configuring NIC and enabling
Creating user 
user privileges
secret  
 Enabling ssh service
setting hostname
generating ssh key
vty
enable ssh v2
Ansible Controller
Manage inventory
Creating host group
Declaring variables: 
ansible_network_os
ansible_connection
ansible_password
Modules
ios_banner 
ios_config  
ios_command 
ios_facts 
ios_user
ios_l3_interface
Arista EOS
Configuring Router
Introduction to EOS
Basic EOS commands
enable
configure terminal
show interfaces
show history
write
ZTP
Disabling ZTP
Setting IP Address
Removing switchport
Configuring NIC 
Creating user 
user privileges
roles
secret  
 Enabling ssh service
setting hostname
enable ssh 
Ansible Controller
Manage inventory
Creating host group
Declaring variables:
ansible_network_os
ansible_connection
ansible_become_method
ansible_python_interpreter (Only if error occurs)
ansible_ssh_user
ansible_ssh_pass
Modules
eos_command
eos_config
eos_user
eos_l2_interface
eos_l3_interface
eos_banner
	
VYOS 
Configuring Router
Introduction to VYOS
Basic VYOS commands
install image
configure
commit 
save
show history
show interface
Setting IP Address
Configuring NIC 
Creating user
user level
admin	
operator
Enabling ssh service
Setting hostname
Enable ssh
Ansible Controller
Manage inventory
Creating host grp
Declaring variables
ansible_connection
ansible_network_os
ansible_ssh_user
ansible_ssh_pass
ansible_python_interpreter (Only if error occurs)
Modules
vyos_banner
vyos_user
vyos_command
vyos_config
vyos_l3_interface





CISCO IOS XR 
Configuring Router
Introduction to CISCO XR
Basic IOS XR commands
configure terminal
show 
commit
Setting IP Address
Configuring NIC and enabling 
Creating user 
user groups
secret  
0 - unencrypted 
5 - encrypted
 Enabling ssh service
setting hostname
generating ssh key
Enable ssh v2
Ansible Controller
Manage inventory
Creating host group
Declaring variables: 
ansible_network_os
ansible_connection
ansible_ssh_user
ansible_ssh_pass
Modules
iosxr_banner 
iosxr_config   
iosxr_user
iosxr_l3_interfaces
iosxr_interface
