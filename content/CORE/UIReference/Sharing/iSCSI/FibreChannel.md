---
title: "Fibre Channel"
weight: 20
alias: /core/sharing/iscsi/fibrechannel/
---

{{< toc >}}

Fibre Channel is a high-speed data transfer protocol providing in-order, lossless delivery of raw block data.
Fibre Channel is primarily used to connect computer data storage to servers in storage area networks in commercial data centers.
The Fibre Channel protocol is fast, cost effective, and reliable over a wide variety of storage workloads.

{{< expand "Which TrueNAS Products can use Fibre Channel?" "v" >}}

* [TrueNAS R-Series](https://www.truenas.com/r-series/)(4x16 Gbps)
* [TrueNAS X-10](https://www.truenas.com/x-series/)(2x8 Gbps)
* [TrueNAS X-20](https://www.truenas.com/x-series/)(2x8 Gbps)
* [TrueNAS M-40](https://www.truenas.com/m-series/)(4x16 Gbps)
* [TrueNAS M-50](https://www.truenas.com/m-series/)(4x16 Gbps or 2x32 Gbps)
* [TrueNAS M-60](https://www.truenas.com/m-series/)(4x32 Gbps)

{{< /expand >}}

Fibre Channel is a TrueNAS Enterprise feature. 
Only TrueNAS systems licensed for Fibre Channel have the **Fibre Channel Ports** tab on the **Sharing > Block Shares (iSCSI)** screen.

{{< hint info >}}
**Initiators** and **Authorized Access** screens only apply to iSCSI block shares and can be ignored when configuring Fibre Channel ports.
{{< /hint >}}

## Fibre Channel Ports


![iSCSWithFiberChannelPorts](/images/CORE/12.0/iSCSWithFibreChannelPorts.png "ISCSI with Fibre Channel Ports")

Use the blue **Columns** button to display options to can change the **Fibre Channel** table display. Options are **Unselect All**, **WWPN**, **State** or **Reset to Defaults**.

Click <i class="material-icons" aria-hidden="true" title="Expand">chevron_right</i> to expand the **Fibre Channel** options. 

![iSCSIFibreChannelPorts](/images/CORE/13.0/iSCSIFibreChannelPorts.png "iSCSI Fiber Channel Ports")

### Fibre Channel Mode Settings
| Setting | Description |
|---------|-------------|
| **Initiator** | Sets the port as an initiator.  |
| **Target** | Sets the port as a target.  |
| **Disabled** | Disables  |

**SAVE** after making any setting change.

## Targets Settings for Fibre Channels 

![Sharing ISCSI Targets Add Fibre](/images/CORE/12.0/SharingISCSITargetsAddFibre.png "ISCSI Targets: Fibre")

The **Targets > Add** screen **Target Mode** dropdown list includes options to select **iSCSI**, **Fibre Channel**, or **Both**.

## Additional Information

For more information on iSCSI see:

[About iSCSI Shares]({{< relref "/CORE/UIReference/Sharing/iSCSI/_index.md" >}})

[The iSCSI Screen]({{< relref "/CORE/UIReference/Sharing/iSCSI/iSCSIShare.md" >}})

[Fibre Channel Ports Screen]({{< relref "/CORE/UIReference/Sharing/iSCSI/FibreChannel.md" >}})

[Adding an iSCSI Share]({{< relref "/CORE/CORETutorials/Sharing/iSCSI/AddingiSCSIShare.md" >}}) 

[Using iSCSI Shares]({{< relref "/CORE/CORETutorials/Sharing/iSCSI/UsingiSCSIShare.md" >}})

[Increasing iSCSI Share Available Storage]({{< relref "/CORE/CORETutorials/Sharing/iSCSI/IncreasingiSCSIAvailableStorage.md" >}})

[Setting Up Fibre Channel]({{< relref "/CORE/CORETutorials/Sharing/iSCSI/SettingUpFibreChannel.md" >}})

[Setting Up NPIV]({{< relref "/CORE/CORETutorials/JailsPluginsVMs/VirtualMachines/SettingUpNPIV.md" >}})
