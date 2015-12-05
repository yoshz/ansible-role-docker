yoshzz.docker
=============

An Ansible role for installing docker on Ubuntu.


Requirements
------------

None


Role Variables
--------------

Configure docker startup options:

    docker_options: "-H unix:///var/run/docker.sock -H tcp://0.0.0.0:4243"


Dependencies
------------

None


License
-------

MIT
