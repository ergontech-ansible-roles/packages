Packages Role
=========

Installs configured apt packages

Role Variables
--------------

```
# Any Vars?

base_packages:
  - htop
  - vim
  - curl
  - wget

cache_valid_time: 86400 #1 Day in seconds

packages_to_remove:

# option to install per group
# group -> web
web_group_packages:
  - nano

```

----------------

```
# requirements.yml

- src: https://github.com/ergontech-ansible-roles/packages
  version: master
  name: packages
```

License
-------

[MIT](LICENSE)