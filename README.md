# ansible-install-cpanel-only
This playbook can be use to install cpanel. Additionally malware detect and ConfigServer Firewall can be installed.  This playbook is inspired from https://github.com/LithiumHosting/ansible-cpanel-bootstrap.

Playbook can be run as

    ansible-playbook -i inventory.ini -l prod sites.yml
