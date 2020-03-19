matthull.venv - Ansible role
=========
[![Build Status](https://travis-ci.org/matthull/ansible-venv.svg?branch=master)](https://travis-ci.org/matthull/ansible-venv)

Sets up one or more venvs

Requirements
------------

`python3` must be on the path.

Role Variables
--------------
Just list one or more locations you'd like to install python to.

```YAML
venv_path: /home/app/pythonenv     # required - the location to create venv at
venv_python_path: /usr/bin/python3.8  # optional - the python to create venv with
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
