# New NetApp FC Data Interface Workflow

## Workflow description and tasks

The New NetApp FC Data Interface workflow creates a Fibre Channel data
interface using either Fibre Channel Protocol or NVMe over Fibre Channel
(NVMe/FC).

![](../images/NewNetAppFCDataInterface/ae25c21b2fae69a86f781a1f45b27ffa0ef8355a.png)

## Workflow inputs
\* indicates the input is required

**Storage Device\***

**Storage Virtual Machine\***

**Interface Name\*:** Name for the new FC data interface.

**Data Protocol\***: Data protocol that can be served by the interface.

**Location Port Name\*:** FC port on which to create the interface.

**Location Port Node Name\*:** Port node being used to create the
interface.

## Example workflow execution

1.  Select the storage device and storage virtual machine.

![](../images/NewNetAppFCDataInterface/b9a0b8d7b0ea268acc78980ba7a5e449e07d526c.png)

![](../images/NewNetAppFCDataInterface/5ad6ed3f2fcc07102d698f28de0bfcd4df9783af.png)

2.  Provide the name of the interface to create. Select the data
    protocol. Provide the name of the FC port and port node.

![](../images/NewNetAppFCDataInterface/0b6a5988894d85c7b09244702cfeaf9fc90dfce3.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/NewNetAppFCDataInterface/b514a141bba274c29244ecde153033a68aa7816d.png)
