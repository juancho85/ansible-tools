# Workstation configuration via ansible
* Requirements: Python
* Ansible

```bash
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

## References
* https://opensource.com/article/18/3/manage-workstation-ansible
* https://docs.ansible.com/ansible/latest/cli/ansible-pull.html

```bash
sudo ansible-pull -U https://github.com/juancho85/ansible-tools.git
```
