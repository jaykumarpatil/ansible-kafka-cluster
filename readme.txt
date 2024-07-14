# ansible-inventory command to validate and obtain information about your Ansible inventory:

ansible-inventory -i inventory --list

# This would execute the ping module on all hosts listed

ansible all -i inventory -m ping


# To execute the playbook

ansible-playbook -i inventory install-kafka.yml -u root -K
