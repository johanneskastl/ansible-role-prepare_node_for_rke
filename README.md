prepare_node_for_rke
=========

Prepare a node to install Kubernetes via Rancher's rke (which needs docker and passwordless SSH access)

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.prepare_node_for_rke' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
