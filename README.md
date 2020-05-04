## Ansible Windows Training Examples

### Run commands on windows host

$ ansible win -m win_ping --ask-pass

$ ansible win -m setup --ask-pass

$ ansible win -m win_whoami --ask-pass
