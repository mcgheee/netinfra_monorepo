# NetInfra MonoRepo

This monorepo contains several sub-projects related to the overall NetInfra project. NetInfra is a method of defining networks as code in a structured yaml file. This structure was created to be authoritative, flexible, and extendable. It is intended to be a single source of truth that configuration management software can ingest to deploy networks. This project was originally published in the proceedings of PEARC.

## Example
An example NetInfra file can be fond in [ansible/group_vars/NetInfra.yml]

## Ansible
Ansible is the original target configuration management platform for NetInfra. Included are several roles designed to work with NetInfra.

### bind9

### kea


