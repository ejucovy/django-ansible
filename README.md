
    pip install ansible
    ansible-playbook -i ansible/ansible_hosts ansible/django.yml --extra-vars='git_repo=git@github.com:username/django-project.git'

Expects that the django project repository:

 * has a requirements.txt file at the root
 * has a settings.py file at the root
 * is using a postgres database with user 'postgres' and no password
