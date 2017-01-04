<p align="right">
    <a href="https://travis-ci.org/epiloque/ansible-tunnelbroker">
        <img src="https://travis-ci.org/epiloque/ansible-tunnelbroker.svg?branch=master"
             alt="build status">
    </a>
        <a href="https://galaxy.ansible.com/epiloque/tunnelbroker">
        <img src="https://img.shields.io/badge/ansible--galaxy-tunnelbroker-blue.svg"
             alt="ansible galaxy">
    </a>
</p>

tunnelbroker role

## Role Variables

Available variables are listed below, along with default values:

```yaml
tunnelbroker_interface: sit1
tunnelbroker_defaultgw: true

# client IPv6 addresss with the mask
tunnelbroker_client_ipv6:

# server IPv4 address
tunnelbroker_server_ipv4:

# server IPv6 without the mask
tunnelbroker_server_ipv6:
```


## Example Playbook

```yaml
- hosts: servers
  roles:
    - epiloque.tunnelbroker
```

## License

BSD
