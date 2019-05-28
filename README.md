# working infra-ansible

ansible-playbook -i inventory/ansible-tower playbooks/ansible/tower/configure-ansible-tower.yml -e "ansible_host=localhost" -t always 
