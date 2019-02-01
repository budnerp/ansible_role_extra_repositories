#  Ansible role for extra repositories
Ansible role for EPEL and Remi's RPM repositories installation for CentOS 7

## Repositories
- EPEL
- Remi's RPM repository [https://rpms.remirepo.net/]()

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_extra_repositories.git ansible_role_extra_repositories
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_extra_repositories # Enable EPEL and Remi's repositories
    [...]
    ```
## Other links
- yum-utils [https://github.com/rpm-software-management/yum-utils]()

## License
Copyright (c) We Are Interactive under the MIT license.