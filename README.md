matthull.venv - Ansible role
=========

Sets up one or more venvs

Requirements
------------

`python3` must be on the path.

Role Variables
--------------
Just list one or more locations you'd like to install python to.

```YAML
venv_paths: - /home/app/pythonenv     #required
venv_python_path: /usr/bin/python3.8  #optional
```

Example Playbook
----------------

```YAML
- hosts: app
  roles:
    - role: matthull.venv
```

License
-------

MIT
