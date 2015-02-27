# FreeBSD: Firewall

This Role allows an administrator to manage a FreeBSD PF based firewall. It allows you to configure:

- Lookup tables for faster address matching;
- TCP services with ports, action (pass, block), from (table, 'any', 'self'), and to (table, 'any', 'self');
- UDP services with the same options as TCP services

The Role can also be used to manage the PF installation for you, enabling the service, loading the kernel module, and enabling PF.

## License

GPLv3

## Author Information
- Michael Crilly
- Autologic Technology Ltd
- http://www.mcrilly.me/
