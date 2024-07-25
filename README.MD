# Workstation Tools

This repository contains scripts to automate and speedup the workflow and preparation for my machine.

> **_Disclaimer_** :
> Those scripts are ubuntu related with major version 18+, for other distributions you'll need to adapt it
___

## Prepare Workstation

> Read the `workstation.yml` file before applying and be sure to understand everything that will be done.

1. Install Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
2. Clone this repository
```bash
git clone https://github.com/alessonviana/Worksation_Ubuntu.git
```

3. Apply the configuration
```bash
ansible-playbook main.yml -i hosts.ini --ask-become-pass
```

>Type your password when asked to give root permissions for some actions.


### Tags that can be used in playbook:
    - update
    - chrome
    - cli  
    - docker 
    - kubectl
    - kubectx 
    - packages 
    - slack 
    - spotifi 
    - terraform 
    - vscode
___

# License
GPLv3

# Author Information
Created by [@bergpb](https://twitter.com/lbergpb) </br>
Edit by [@alessonviana](https://alessonviana.tech)

Contributions are more than welcome!