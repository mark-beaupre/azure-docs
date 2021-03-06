<a name="virtual-networking-limits-classic"></a>The following limits apply only for networking resources managed through the classic deployment model per subscription.

| Resource | Default limit | Maximum limit |
| --- | --- | --- |
| Virtual networks |50 |100 |
| Local network sites |20 |contact support |
| DNS Servers per virtual network |20 |100 |
| Private IP Addresses per virtual network |4096 |4096 |
| Concurrent TCP or UDP flows per NIC of a virtual machine or role instance |500K |500K |
| Network Security Groups (NSG) |100 |200 |
| NSG rules per NSG |200 |400 |
| User defined route tables |100 |200 |
| User defined routes per route table |100 |400 |
| Public IP addresses (dynamic) |5 |contact support |
| Reserved public IP addresses |20 |contact support |
| Public VIP per deployment |5 |contact support |
| Private VIP (ILB) per deployment |1 |1 |
| Endpoint Access Control Lists (ACLs) |50 |50 |

#### <a name="azure-resource-manager-virtual-networking-limits"></a>Networking Limits - Azure Resource Manager
The following limits apply only for networking resources managed through Azure Resource Manager per region per subscription.

| Resource | Default limit | Maximum Limit |
| --- | --- | --- |
| Virtual networks |50 |500 |
| Subnets per virtual network |1,000 |contact support |
| DNS Servers per virtual network |9 |25 |
| Private IP Addresses per virtual network |4096 |8192 |
| Private IP Addresses per network interface |50 |contact support |
| Concurrent TCP or UDP flows per NIC of a virtual machine or role instance |500K |500K |
| Network Interfaces (NIC) |300 |10000 |
| Network Security Groups (NSG) |100 |400 |
| NSG rules per NSG |200 |500 |
| User defined route tables |100 |200 |
| User defined routes per route table |100 |400 |
| Public IP addresses (dynamic) |60 |contact support |
| Public IP addresses (Static) |20 |contact support |
| Load Balancers (internal and internet facing) |100 |contact support |
| Load Balancer rules per load balancer |150 |150 |
| Load Balancer rules per IP configuration |299 |299 |
| Public front end IP per Load Balancer |10 |30 |
| Private front end IP per Load Balancer |10 |contact support |
| VNets peerings per Virtual Network |10 |50 |
| Point-to-Site Root Certificates per VPN Gateway |20 |20 |
| Secondary IP configurations per virtual network |1000 |contact support |

[Contact support](../articles/azure-supportability/resource-manager-core-quotas-request.md ) in case you need to increase limits from default.

