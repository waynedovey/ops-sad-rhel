--- 
# ops-sad-rhel-docker

Install 

ansible-playbook deploy_docker.yml --tags "install" -b

Delete * Warning this does a node reboot 

ansible-playbook deploy_docker.yml --tags "delete" -b

--- 
# ops-sad-rhel-partitions

Install 

ansible-playbook deploy_partitions.yml --tags "create" -b

Delete 

ansible-playbook deploy_partitions.yml --tags "delete" -b
