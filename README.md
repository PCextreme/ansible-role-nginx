# Ansible Role: Nginx

Installs Nginx

## Supported platforms

```
CentOS 6 & 7
Ubuntu 14.04
```

## Requirements

None

## Role Variables

Nginx version:

```
nginx_mainline: true
```

## Dependencies

None

## Example Playbook

```
- hosts: servers
  roles:
    - { role: pcextreme.nginx }
```

## Credits

- [Attila van der Velde](https://github.com/vdvm)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
