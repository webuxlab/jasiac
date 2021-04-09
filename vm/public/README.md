# Public VM

```bash
ansible-playbook -i 192.168.2.31, 01_filsystem.yml --ask-become --user root
ansible-playbook -i 192.168.2.31, 02_file_structure.yml --ask-become --user root
ansible-playbook -i 192.168.2.31, 03_install_utilities.yml --ask-become --user root
ansible-playbook -i 192.168.2.31, 04_docker_install.yml --ask-become --user root
```
