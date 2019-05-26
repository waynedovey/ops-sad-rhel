# ops-sad-rhel-docker

# Install 
ansible-playbook deploy_docker.yml --tags "install" --skip-tags "delete" -b

# Delete ** Warning this does a node reboot 
ansible-playbook deploy_docker.yml --tags "delete" --skip-tags "install" -b
