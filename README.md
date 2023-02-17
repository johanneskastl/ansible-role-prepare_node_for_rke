prepare_node_for_rke
=========

Prepare a node to install Kubernetes via Rancher's rke (which needs docker and passwordless SSH access)

Requirements
------------

None.

Role Variables
--------------

- `ssh_key_to_add`: (required) public SSH key to add to the user's `~/.ssh/authorized_keys` file
- `user_to_add_ssh_key_to`: (optional) Name of the user that you want to modify, defaults to the `ansible_user`

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.prepare_node_for_rke'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
