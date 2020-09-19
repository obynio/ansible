# Ansible

> One ring to rule them all

These are my Ansible roles that I use to setup my infrastructure.
These playbook were designed to run against ArchLinux.

You can run the playbooks using `ansible-playbook playbook/base.yml` or `vagrant provision`.
When running on localhost, put the repository in `/etc/ansible`.

## Vault

I use `ansible-vault edit|create myfile.yml` to keep sensitive data such as passwords or keys in encrypted files, rather than as plaintext.

```
# Create a vault file
ansible-vault create vault.yml

# Edit a vault file
ansible-vault edit vault.yml
```
