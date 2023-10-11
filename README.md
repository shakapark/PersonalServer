# PersonalServer

## Ansible install

```bash
sudo apt install python3-pip
sudo pip3 install --upgrade pip
sudo pip3 install --user -r ./requirements.txt
```

## Use Playbook

```bash
ansible-playbook -i Ansible/hosts -K Ansible/PersonalServer-playbook.yml
```