# Block russian IP address ranges in RouterOS

1. Make sure you can connect to your RouterOS router via SSH.

2. Create IPv4 and IPv6 address lists.

```
ssh username@your_router < routeros_russian_ipv4_ranges_routeros_address-list.lst
ssh username@your_router < routeros_russian_ipv6_ranges_routeros_address-list.lst
```

3. Create firewall rules.

```
routeros_firewall_rules.lst
```