apt_source
==========

This role configures the mirror for apt sources for Debian and Ubuntu based systems on x86 and also arm for Raspberry Pi.

Role Variables
--------------

| Name                     | Comment                              | Default value                    |
|--------------------------|--------------------------------------|----------------------------------|
| apt_debian_source_mirror | The mirror URL for Debian to be used | `http://mirror.init7.net/debian` |
| apt_ubuntu_source_mirror | The mirror URL for Ubuntu to be used | `http://mirror.init7.net/ubuntu` |

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_base.apt_source
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
