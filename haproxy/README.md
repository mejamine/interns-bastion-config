run :
ansible-playbook playbooks/main.yml --ask-become-pass

************the back to the line in the haproxy.cfg is required *******************



sudo setsebool -P httpd_can_network_connect 1
