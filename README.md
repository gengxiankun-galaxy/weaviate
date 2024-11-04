Weaviate
=========

通过 `ansible` 部署在容器下运行的 Weaviate 服务。

Installation
------------

`ansible-galaxy install gengxiankun.weaviate`

Dependencies
------------

- [Docker](https://github.com/gengxiankun-galaxy/docker)

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.weaviate

License
-------

BSD

Author Information
------------------

This role was created in 2024 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).