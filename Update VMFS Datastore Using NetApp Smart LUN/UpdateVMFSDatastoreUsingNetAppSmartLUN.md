# Update VMFS Datastore Using NetApp Smart LUN Workflow

## Workflow description and tasks

The Update VMFS Datastore Using NetApp Smart LUN workflow expands the
capacity of the underlying storage volume/LUN, and then grows the
datastore to utilize the additional capacity.

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/0024dc8589ac48e7f9e6289d4f674aee46970180.png)

## Workflow inputs
\* indicates the input is required

### Hypervisor inputs:

- **Hypervisor Manager\*:** Hypervisor manager managing the cluster in the
datacenter.

- **Datacenter\*:** Datacenter associated with the cluster where the
datastore is hosted.

- **Cluster:** Cluster on which the datastore will be hosted.

- **Host:** Host on which the datastore will be hosted. If the cluster is
specified, the host parameter will be ignored.

- **Datastore\*:** Name of the datastore for which capacity is to be
expanded

- **Datastore Capacity\*:** New size of the datastore

### Storage inputs:

- **Storage Device\***

## Example workflow execution

1.  Select the hypervisor manager, datacenter, cluster or host, and
    datastore for which capacity is to be expanded.

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/23107a99082e191f17d3ede817635afc2f4ce986.png)

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/7c0621128a7799fe905997fc4928345e579ffc2b.png)

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/10aeed8d79ff126e318d9eaa2c438e4eb4a116a4.png)

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/d5106bd0a97ab67a513823457c9a09cf6dd264c4.png)

2.  Provide the updated datastore capacity.

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/e16bc790b219804007c81c4b6ff383dfc20b26d1.png)

3.  Select the storage device.

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/2d68c1b1c2b5f15165f1f536681b91c1c8adbc08.png)

4.  Review your input selections for correctness, then click **Execute**.

5.  View workflow execution details on the History tab.

![](../images/UpdateVMFSDatastoreUsingNetAppSmartLUN/02bff92a0066d6c1dc4aeaf31daad4cee679a8ce.png)