# ansible-vault-wrapper

Overview
--------
Simple bash wrapper to execute Ansible vault commands in a more convenient way:
   ```
   #########################
   # Ansible Vault Wrapper #
   #########################

   Usage:
     ansible-vault-wrapper [Options] <Args>

   Options:
     -c    Cleanup vault files cache file
     -d    Decrypt all vault files
     -e    Encrypt all vault files
     -h    Show this help text
     -r    Rekey (change password for) all vault files
     -s    Search for secret text in all vault files

   Example:
     ansible-vault-wrapper -s  
   ```

Prerequisites
-------------
* [Ansible](https://docs.ansible.com/ansible/2.7/installation_guide/intro_installation.html) must be installed

Installation
------------
* Download ansible-vault-wrapper script to `/usr/local/bin` folder:

   ```
   sudo wget https://raw.githubusercontent.com/chrisipa/ansible-vault-wrapper/master/ansible-vault-wrapper -O /usr/local/bin/ansible-vault-wrapper
   ```
   
* Make ansible-vault-wrapper script executable:   

   ```
   sudo chmod +x /usr/local/bin/ansible-vault-wrapper
   ```
