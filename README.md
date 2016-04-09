# iocage-tools
Script for ZFS based jails with iocage so we can do thin clones

## Typical usage

```
ioc-setup
ioc-newtemplate common "lo2|10.7.7.100/32"
ioc-newjail common myjail "lo2|10.7.7.100/32"
```
