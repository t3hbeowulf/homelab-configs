# HomeLab Configs
Within this repository are a collection of Ansible and Terraform configurations that define, configure and maintain my homelab. 
As of 2024-02-01, this is a _very early_ work in progress. 

## Goals
### Hardware
1. Define each node configuration
1. Define node grouping configuration
1. Define networking configuration

### Ansible
1. Define base tasks for all Proxmox hosts in my homelab
1. Define base VM tasks for initial VM configuration to reduce the number of VM templates required
1. Define custom VM tasks for specific VMs to ensure rapid recreation

### Terraform
1. Define ProxMox VM Creation with parameters
1. Define ProxMox LXC Creation with parameters
1. Define a VM Suite that stands up Kubernetes