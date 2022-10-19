# consulService
Forked project to update host

We have 2 VM.

- n1 -> 192.168.100.4
- n2 -> 192.168.100.3

## VM n1 will be the main server in charge of load balancing using HAProxy

## Getting started

Run "vagrant up". There are two bash scripts that will provision the machines.

Once the setup is completed you can check the status using these urls:

### Consul dashboard
http://192.168.100.3:8500/ui/dc1/services/web/instances

### HAProxy stats
http://192.168.100.3:1936/

### URL for load balancing
http://192.168.100.3/

