goss-module
=========

This role allows the use of the goss module (https://github.com/indusbox/goss-ansible).


Requirements
------------

Tested with Ansible 1.8.2, Ansible 1.9.6, Ansible 2.0.2

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: goss-module }
      tasks:
         - name: Execute test file with json output
           goss:
             path: "~/goss/goss.yaml"
             format: "json"

License
-------

MIT

More Informations
------------------

More informations about Goss : https://github.com/aelsabbahy/goss
More informations about the goss module : https://github.com/indusbox/goss-ansible
