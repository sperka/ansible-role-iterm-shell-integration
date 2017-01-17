iTerm2 shell integration ansbile role
=====================================

An Ansible role that installs iTerm2 shell integration. For more information,
check [iTerm2 shell integration](https://www.iterm2.com/documentation-shell-integration.html)

Requirements
------------

None

Role Variables
--------------

```ansible
    shell_integration_script: install_shell_integration.sh
    base_url: https://iterm2.com/misc
```

Dependencies
------------

None

Example Playbook
----------------

```ansible
    - name: Install iTerm2 shell integration
      hosts: my-servers
      roles:
        - { role: sperka.iterm2-shell-integration }
```

License
-------

MIT
