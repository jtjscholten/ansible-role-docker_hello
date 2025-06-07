# Ansible Role: docker_hello

Deze Ansible rol installeert en configureert Docker op Ubuntu systemen.

## Requirements

- Ansible >= 2.9
- Ondersteunde platformen:
  - Ubuntu 20.04 (Focal)
  - Ubuntu 22.04 (Jammy)

## Role Variables

Zie `defaults/main.yml`.

## Example Playbook

```yaml
- hosts: all
  roles:
    - docker_hello
```

## License

MIT

## Author Information

Jeroen Scholten
