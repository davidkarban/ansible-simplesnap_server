Simplesnap_server
=========

Backup your ZFS machines by simplesnap. Role installs simplesnap onto your backup server and setup regular backup run. 

Role Variables
--------------

simplesnap_backup_interval: 
  - how often should simplesnap run (in hours).


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: backup_servers
      roles:
         - { role: davidkarban.simplesnap_server, simplesnap_backup_interval: 1 }

License
-------

GPLv3

Author Information
------------------

David Karban

email: david@karban.eu

web: www.karban.eu

Jan Pechek

email: honza@pechek.cz
