wsl2-tools
----------

A collection of utilities for use in a WSL2 environment

To install, include the `bin` directory in your PATH.

## Tools
### wsl2-ip
Lists the IP address of the current wsl2 machine.

```
wsl2-ip
172.29.51.156
```

### wsl2-proxy-port-list
Lists all host-to-wsl port proxies

```
wsl2-proxy-port-list

Listen on ipv4:             Connect to ipv4:

Address         Port        Address         Port
--------------- ----------  --------------- ----------
0.0.0.0         80          172.29.51.156   80
0.0.0.0         22          172.29.51.156   22
```

### wsl2-proxy-port-add
Add a host-to-wsl port proxy. Will prompt for windows admin access.

```
wsl2-proxy-port-add 80
```

### wsl2-proxy-port-del
Remove a host-to-wsl port proxy. Will prompt for windows admin access.

```
wsl2-proxy-port-del 80
```

### wsl2-proxy-port-clear
Removes all host-to-wsl port proxies. Will prompt for windows admin access.

```
wsl2-proxy-port-clear
```
