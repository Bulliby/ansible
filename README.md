# Ansible

## Vitualbox

```shell
vboxmanage startvm ArchRox --type headless
```

## AdHoc

```shell
ansible -i inventory.yml archrox -m script -a '/bin/ls /'
```

## PlayBook

```shell
ansible-playbook -i inventory.yml -e @group_vars/vault.yml --vault-password-file ~/.vault playbook.yml
```
