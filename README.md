# Ansible Playbooks

## Kali

```bash
sudo apt update && sudo apt install ansible -y
curl https://raw.githubusercontent.com/OlivierProTips/ansible/master/playbooks/kali-setup.yml -o /tmp/kali-setup.yml
ansible-playbook /tmp/kali-setup.yml
```