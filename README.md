## install ansible

1. [clone repo](https://github.com/Roarain/ansible-install-2.7.16)

## install redis cluster

```
ansible-playbook -i inventory/inventory.ini install.yaml
```

## uninstall redis cluster

```
ansible-playbook -i inventory/inventory.ini uninstall.yaml
```