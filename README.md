# Ansible Playbooks

This repository has playbooks for installing various components that may be needed for moving to Azure.

## Roles

### ASR

This role will install the ASR Migration agent.  Please see the README file inside the role directory 
for the needed information necessary to use that role. Please review the inventory file in this repository
in conjunction with the README file in the specific role directory for examples of the information needed
by the playbook during execution.

### WALinuxAgent

This role will install the WALinuxAgent on certain Linux distros.  The currently supported distros are:
* Oracle Linux (7.6 and 7.7)
* Ubuntu (16.04 and 18.04)