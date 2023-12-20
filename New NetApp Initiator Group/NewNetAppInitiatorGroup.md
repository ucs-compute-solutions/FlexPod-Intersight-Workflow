# New NetApp Initiator Group Workflow

## Workflow description and tasks

The New NetApp Initiator Group workflow creates a new initiator group.

![](../images/NewNetAppInitiatorGroup/fc8abc521f5002872eba55e242bcbc766dbef3b8.png)

## Workflow inputs
\* indicates the input is required

- **Storage Device\***

- **Storage Virtual Machine\***

- **Initiator Group Name\*:** The name of the initiator group.

- **Protocol:** The protocol(s) supported by the initiator group (iSCSI,
FCP, or Mixed).

- **Operating System\*:** The host operating system of the initiator
group. All initiators in the group should be hosts of the same operating
system. The default is VMware.

- **Initiators:** The initiator(s) to add to the new initiator group. Use
Fibre Channel (FC) world wide port names (WWPNs), iSCSI qualified names
(IQNs), and/or iSCSI extended unique identifiers (EUIs) to identify host
initiators.

## Example workflow execution

1.  Select the storage device and storage virtual machine.

![](../images/NewNetAppInitiatorGroup/934fd99db84750b3c03eb21973e285c0e133dc95.png)

![](../images/NewNetAppInitiatorGroup/cdd5614e54556beb15b724cbc39c35ea7dcb4383.png)

2.  Provide the initiator group name, protocol, operating system, and
    the initiator(s) to add to the initiator group.

![](../images/NewNetAppInitiatorGroup/5c2eeee658c067abf14a61e4ed472c8aa0c3bf1e.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/NewNetAppInitiatorGroup/b147ad1ba6d9f622602a8bbf988764edf12816b7.png)