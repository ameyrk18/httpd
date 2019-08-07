# httpd

This role installs and configures default apache role. Enables seliniux. 

Vars are defined in https://github.com/ameyrk18/httpd/blob/master/vars/main.yml

# Execute this playbook  
``ansible-playbook -i inventory playbook.yml --private-key <private-key> --extra-vars "ansible_user=<user>" ``
 

 1. Update your inventory file accordingly 
 2. Private key and username must be defined 
 
 
# Valid CA certs 
If you are looking to use valid CA certs then please place your certs under ``certs`` directory  provided and update the ``ssl_type:signed``


