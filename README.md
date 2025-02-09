# Ansible_Playbooks

## playbook.yaml
A general purpose ansible-playbook that ensures some packages are installed/uninstalled, sets the group for the `ansible` user on the servers, then checks a mysql server.

## ubuntu.yaml
Keeps all the ubuntu/debian/raspian updated.

## python.yaml
Ensures all the required packages to compile python exist.
Pulls python 3.13.3 into a directory.
It does not compile it... I stopped short.

# Ansible Lint
`pip install ansible-lint`

`ansible-lint <playbook>`
