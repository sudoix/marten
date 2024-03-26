# marten
![marten](./marten.png)
=========

This is simple project to create something like [Shecan](https://shecan.ir/).

Requirements
------------

Create your inventory file from `inventory.ini.sample`
```sh
cp inventory.ini.sample inventory.ini
```

Variables
--------------

To add new domain, edit the `group_vars/all.yml`. Also, You can edit other variables in `group_vars`.

Dependencies
------------

- Ansible (deployer system)
- Docker (on servers) - https://docs.docker.com/engine/install/ubuntu/
- Docker-Compose (on servers) - https://docs.docker.com/compose/install/

Usage
----------------

Just run:
```sh
ansible-playbook site.yml -i inventory.ini -b
```

License
-------

GNU General Public License v3.0