# first_ansible_task
ssh -i ansibleTask.pem ubuntu@52.206.186.12
mkdir ~/.ssh
nano ~/.ssh/id_rsa   
chmod 400 ~/.ssh/id_rsa
nano inventory.ini
nano frontend.yml
nano docker.yml
ansible-playbook -i inventory.ini frontend.yml
ansible-playbook -i inventory.ini docker.yml

