Common Variables
================

## Networking

- `ryezone_labs_provision_user` (string)

  This value sets the owner of the ssh keys for the provisioning user.

  Usages:
    - [ryezone_labs.ansible_control_server](https://github.com/ryezone-labs/ansible_control_server)

- `ryezone_labs_external_dns` (list of string)

  List of external DNS servers to use.

  Usages:
    - [ryezone_labs.dhcp](https://github.com/ryezone-labs/dhcp)
    - [ryezone_labs.dns](https://github.com/ryezone-labs/dns)

- `ryezone_labs_domain_admin_password` (string)

  Password to use for the default admin account `cn=admin,dc={{ dc_org }},dc={{ dc_suffix }}`.
  
  Defaults to `My$uper$ecretP@$$w0rd`.

  Usages:
    - [ryezone_labs.domain_controller_slapd](https://github.com/ryezone-labs/domain_controller_slapd)

- `ryezone_labs_domain_organization` (string)

  Organization name to use when creating the domain.
  
  Defaults to `domain`.

  Usages:
    - [ryezone_labs.domain_controller_slapd](https://github.com/ryezone-labs/domain_controller_slapd)

- `ryezone_labs_domain_suffix` (string)

  Domain suffix to use when creating the domain.
  
  Defaults to `local`.

  Usages:
    - [ryezone_labs.domain_controller_slapd](https://github.com/ryezone-labs/domain_controller_slapd)

- `ryezone_labs_lanInterface` (string)

  Sets the LAN interface on the edge node.

  Usages:
    - [ryezone_labs.dhcp](https://github.com/ryezone-labs/dhcp)

- `ryezone_labs_lanAddress` (string)
- `ryezone_labs_lanNetwork` (string)
- `ryezone_labs_lanNetmask` (string)
- `ryezone_labs_lanBroadcast` (string)
- `ryezone_labs_lanDhcpRangeStart` (string)
- `ryezone_labs_lanDhcpRangeEnd` (string)

- `ryezone_labs_top_level_domain` (string)

  Sets the top level domain for DNS and DHCP.

  Usages:
    - [ryezone_labs.ansible_control_server](https://github.com/ryezone-labs/ansible_control_server)
    - [ryezone_labs.dhcp](https://github.com/ryezone-labs/dhcp)

- `ryezone_labs_wanInterface` (string)

  Sets the WAN interface on the edge node.
  Usages:
    - [ryezone_labs.dhcp](https://github.com/ryezone-labs/dhcp)

