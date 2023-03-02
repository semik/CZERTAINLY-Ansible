# CZERTAINLY-Ansible
Content of `/etc/czertainly-ansible` directory for CZERTAINLY appliance.

## Intialization was done:
```
cd CZERTAINLY-Ansible
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-czertainly-branding.git roles/branding
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-http-proxy.git roles/http-proxy
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-postgres.git roles/postgres 
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-helm.git roles/helm 
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-rke2.git roles/rke2 
git submodule add -b develop https://github.com/3KeyCompany/ansible-role-czertainly.git roles/czertainly
```
