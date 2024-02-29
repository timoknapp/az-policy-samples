# Azure Policy Samples

This repo contains a collection of Azure Policy definitions that can be used to enforce different rules and effects within Azure. The policies are defined using JSON and are split into different categories within the repo.

## Network

- [Deny NSG rule that allows any (`*`) inbound traffic](definitions/network/deny-nsg-rule-inbound-allow-all.json)
- [Enforce NSG on subnets](definitions/network/deny-subnet-without-nsg.json)
- [Enforce NSG on subnets for VNETs](definitions/network/deny-vnet-when-subnets-missing-nsg.json)

