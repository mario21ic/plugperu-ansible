# Ansible playbook example

Instalar requisitos:
```
pip install ansible
pip install molecule[docker]
```

Ejecutar playbook:
```
ansible-playbook playbook.yml
```

Ejecutar testing paso a paso:
```
molecule create
molecule list
molecule converge
molecule verify
```

Ejecutar testing todo en uno:
```
molecule test --destroy never
molecule login # en caso de error
molecule destroy --all
```
