Role Name
=========
configuration the  nfs-client through automation on linux based server

Requirements
------------

no special requirement

Role Variables
--------------
some  variables are listed below along with their default value:
1. nfs server detail
nfs_server: 35.153.135.50 
2. directory which i have created on nfs-server 
server_dir: /games 
3. directory which i have created on nfs-client
client_dir: /mnt/jyoti

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: client
      roles:
         - nfs-client.yml


Author Information
------------------
name = jyoti chaudhary
