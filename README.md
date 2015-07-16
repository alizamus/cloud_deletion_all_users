# cloud_deletion_all_users
This repository is to run Ansible code which delete all of the users and its corresponding openstack and contrail changes.
1- You should run this python code in playbook directory to generate the necessary variables to delete the projects.
python config.py
2- Then you shoud run command below to actually start deletion process.
ansible-playbook all_user_deletion.yml
