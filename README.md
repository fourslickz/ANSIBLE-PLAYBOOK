## check list of hosts
- ansible-inventory -i hosts --list

## run for spesific host
- ansible 103.150.190.11 -m ping
- ansible-playbook install_mysql.yml -l 103.150.190.11
- ansible -i hosts sasakti -m ping
- ansible-playbook -i hosts ./sasakti/install_postgresql_ubuntu_22.04.yml --limit=sasakti

