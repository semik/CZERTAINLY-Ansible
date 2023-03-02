# CZERTAINLY-Ansible
Content of `/etc/czertainly-ansible` directory for CZERTAINLY appliance.

git submodule [howto](https://www.vogella.com/tutorials/GitSubmodules/article.html#delete-a-submodule-from-a-repository).

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

## Update after checkout
```
git submodule update --init --recursive -j 8
```
