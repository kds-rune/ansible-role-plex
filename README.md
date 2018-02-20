# Ansible Role: plex

A simple Ansible role for installing a plex media server from official repository.

After installation, you can access the server from the following URL to configure:

`http://<hostname>:32400/web`

## Requirements

None

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: perplexed
  gather_facts: True
  tasks:

  - include_role:
      name: noruro.plex
    vars:
      plex_version: latest
```
## License

  MIT

## Author Information

  N/A
