---
title: Azure Virtual Desktop
geekdocCollapseSection: true
geekdocHidden: false
---

## Dependent Azure Resource Recommendations

| Recommendation                                                                                                                                                                                                                                                                  |  Provider Namespace   |     Resource Type      |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------:|:----------------------:|
| [Create a validation host pool](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/DesktopVirtualization/hostPools/#Create-a-validation-host-pool)                                                   | DesktopVirtualization |       hostPools        |
| [Configure host pool scheduled agent updates](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/DesktopVirtualization/hostPools/#configure-host-pool-scheduled-agent-updates)                                                                                     | DesktopVirtualization |       hostPools        |
| [Ensure a unique OU is used when deploying host pools with domain joined session hosts](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/DesktopVirtualization/hostPools/#ensure-a-unique-ou-is-used-when-deploying-host-pools-with-domain-joined-session-hosts) | DesktopVirtualization |       hostPools        |
| [Create scaling plans per region](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/DesktopVirtualization/scalingPlans/#create-scaling-plans-per-region)                        | DesktopVirtualization |      scalingPlans      |
| [Replicate your image templates to a secondary region](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/VirtualMachineImages/imageTemplates/#replicate-your-image-templates-to-a-secondary-region)                                                               |        Compute        |       virtualMachineImages        |
| [Create image Versions replicas in secondary region](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/compute/galleries/#create-image-versions-replicas-in-secondary-region)                                                               |        Compute        |       galleries        |
| [Configure image version replica count per region](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/compute/galleries/#configure-image-version-replica-count-per-region)                                                               |        Compute        |       galleries        |
| [A minimum of three replicas should be kept for production image versions](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/galleries/#a-minimum-of-three-replicas-should-be-kept-for-production-image-versions)                                         |        Compute        |       galleries        |
| [Zone redundant storage should be used for image versions](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/galleries/#zone-redundant-storage-should-be-used-for-image-versions)                                                                         |        Compute        |       galleries        |
| [Deploy VMs across Availability Zones](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/virtualMachines/#deploy-vms-across-availability-zones)                                                                                                           |        Compute        |    virtualMachines     |
| [Backup VMs with Azure Backup service](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/virtualMachines/#backup-vms-with-azure-backup-service)                                                                                                           |        Compute        |    virtualMachines     |
| [Mission Critical Workloads should consider using Premium or Ultra Disks](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/virtualMachines/#mission-critical-workloads-should-consider-using-premium-or-ultra-disks)                                                                                                   |        Compute        |    virtualMachines     |
| [Configure diagnostic settings for all Azure Virtual Machines](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Compute/virtualMachines/#configure-diagnostic-settings-for-all-azure-virtual-machines)                                                           |        Compute        |    virtualMachines     |
| [Connect on-prem networks to Azure critical workloads via multiple ExpressRoutes](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Network/expressRouteCircuits/#connect-on-prem-networks-to-azure-critical-workloads-via-multiple-expressroutes)                |        Network        |  expressRouteCircuits  |
| [Ensure ExpressRoute's physical links connect to distinct network edge devices](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Network/expressRouteCircuits/#ensure-expressroutes-physical-links-connect-to-distinct-network-edge-devices)                     |        Network        |  expressRouteCircuits  |
| [Use Zone-redundant ExpressRoute gateway SKUs](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Network/virtualNetworkGateways/#use-zone-redundant-expressroute-gateway-skus)                                                                                    |        Network        | virtualNetworkGateways |
| [Ensure that storage accounts are zone or region redundant](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Storage/storageAccounts/#ensure-that-storage-accounts-are-zone-or-region-redundant)                                                                 |        Storage        |    storageAccounts     |
| [Configure Service Health Alerts](../../../Azure-Proactive-Resiliency-Library-v2/azure-resources/Subscription/subscriptions/#configure-service-health-alerts)                                                                                                                  |       Subscription        |   subscriptions    |

<br>

## General Workload Guidance

{{< azure-specialized-workloads-recommendationlist name="azure-specialized-workloads-recommendationlist" >}}
