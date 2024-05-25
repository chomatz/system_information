# system_information
ansible role for fastfetch deployment

## requirements

## variables

## dependencies

## examples
```
- name: deploy fastfetch
  ansible.builtin.include_role:
    name: system_information
    tasks_from: fastfetch_deploy.yml
```
