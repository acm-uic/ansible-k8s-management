# ansible-k8s-management
A playbook for setting up a Kubernetes management plane

## Playbook variables

`cluster_name` - This is the name of the cluster. This should be a hostname portion of an FQDN. This hostname should be DNS load balanced by your router or DHCP service.

`base_domain` - This is the name of your domain name all hostnames residing in your infrastructure. (e.g. acmuic.org)
