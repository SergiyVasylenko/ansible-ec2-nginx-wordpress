# ansible-ec2-nginx-wordpress
Ansible Playbook for provisioning ec2 instance Ubuntu, with nginx, php7.2, MySQL 5.6.40, latest wordpress, Letsencrypt SSL certificate deploy, redirect http -> https.
Run with command
ansible-playbook -i hosts --ask-vault-pass playbook.yml
Variables file: vars-web.yml
For terminate aws instance, run command:
ansible-playbook -i hosts --ask-vault-pass ec2-terminate.yml
