ansible -i inventories/hosts --connection=local local -m ping

ansible -i inventories/hosts --connection=local local -m shell -a 'date'

ansible-playbook -i inventories/hosts dir.yml

ansible-lint dir.yml
