# Ansible

## AdHoc

```shell
ansible -i inventory.yml archrox -m script -a '/bin/ls /'
```

## PlayBook

```shell
ansible-playbook -i inventory.yml playbook.yml
```
