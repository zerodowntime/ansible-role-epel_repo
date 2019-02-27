# epel_repo

Ansible role install repo EPEL

## Installation

```yaml
   ansible-galaxy install zerodowntime.epel_repo
```

## Requirements

This role requires Ansible 2.5 or higher.

Supported platforms:

```yaml
  platforms:
    - name: EL
      versions:
        - 7
```

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:

  - role: zerodowntime.epel_repo
```

## License

[Apache License 2.0](LICENSE)

## Support

ansible@zerodowntime.pl
