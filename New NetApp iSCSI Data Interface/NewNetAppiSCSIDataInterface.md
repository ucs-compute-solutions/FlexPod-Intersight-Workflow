# New NetApp iSCSI Data Interface Workflow

## Workflow description and tasks

The New NetApp iSCSI Data Interface workflow creates an iSCSI data
interface.

![](../images/NewNetAppiSCSIDataInterface/911818130753bbd84e32f45fa4b17e595d5ef35f.png)

## Workflow inputs
\* indicates the input is required

- **Storage Device\***

- **Storage Virtual Machine\***

- **Interface Name\*:** Name for the new iSCSI data interface.

- **Home Node\*:** Home node is the node to which the interface returns
when the network interface revert command is run.

- **Home Port:** Home port is the port to which the interface returns when
the network interface revert command is run.

- **Broadcast Domain:** Broadcast domain contains the home port of the
logical interface.

- **Interface IP Address\*:** IP address for the interface

- **Interface Netmask\*:** Netmask for the interface

## Example workflow execution

1.  Select the storage device and storage virtual machine.

![](../images/NewNetAppiSCSIDataInterface/971b9f73c467e9f8a92087ba74e68c49a36683b7.png)

![](../images/NewNetAppiSCSIDataInterface/adaf762f59ea92a9b5807a7d242ed212a72291c0.png)

2.  Provide the name of the interface and home node. The home port and
    broadcast domain are optional. Provide the IP address and netmask to
    use for the interface.

![](../images/NewNetAppiSCSIDataInterface/0cffc9c83b208941ea4daf718648f3976667de33.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/NewNetAppiSCSIDataInterface/2addc688d5e55fa65d14ec1d37bac4401aaea281.png)