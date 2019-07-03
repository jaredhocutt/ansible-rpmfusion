# RPM Fusion

This role handles installing the RPM Fusion repositories on a Fedora system.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.rpmfusion
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
