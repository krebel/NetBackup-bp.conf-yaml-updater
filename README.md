# ansiblestuff
Assumes the ansible server's /etc/ansible/hosts 'nbrhelclnts' is the list of remote NB RHEL clients.
Updates the remote NB RHEL clients' bp.conf to append the DB_SCRIPT_PATH directive to point to the database backup script. (New
requirement starting in NB 8.1).
