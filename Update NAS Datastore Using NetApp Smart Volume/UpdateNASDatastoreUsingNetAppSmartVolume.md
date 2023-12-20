# Update NAS Datastore Using NetApp Smart Volume Workflow

## Workflow description and tasks

The Update NAS Datastore Using NetApp Smart Volume workflow updates a
NAS datastore by updating the capacity of the underlying NFS volume. The
updated capacity is visible to all hosts connected to the datastore.

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/814e254a82093c67063f4885e2dd8fce985ae0ce.png)

## Workflow inputs
\* indicates the input is required

### Hypervisor inputs:

- **Hypervisor Manager\*:** Hypervisor manager managing the cluster in the
datacenter.

- **Datacenter\*:** Datacenter associated with the cluster where the
datastore is hosted.

- **Cluster:** Cluster on which the datastore is hosted.

- **Host:** Host on which the datastore is hosted. If the cluster is
specified, the host parameter will be ignored.

- **Datastore\*:** Name of the datastore for which capacity is to be
updated

- **Datastore Capacity\*:** New size of the datastore

### Storage inputs:

- **Storage Device\***

## Example workflow execution

1.  Select the hypervisor manager, datacenter, cluster or host, and
    datastore for which capacity is to be updated.

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/272bb00437fbfb3c1f5181cc243b4e27f44eeeb1.png)

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/d8fabb3778d9f8f316719f7dca1a49752bc0a1cf.png)

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/7d90eea5fdf5a3d606bc958543ff01b515cfdd21.png)

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/6395659aed854af244c5ece09b4b7a2d5b93cb7c.png)

2.  Provide the updated datastore capacity.

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/1524deffdebeb36ef87520690143a10d5910d395.png)

3.  Select the storage device.

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/31cf7b741786d528a2ae4d6689ac9b68e9bba5a4.png)

4.  Review your input selections for correctness, then click **Execute**.

5.  View workflow execution details on the History tab.

![](../images/UpdateNASDatastoreUsingNetAppSmartVolume/2f8a46c13a32a89d204744f01cf1fac6f2bfdd48.png)

**NOTE:** Expand Hypervisor Datastore is the underlying task called Update
Hypervisor Datastore in this workflow. It can be used to expand or
shrink a datastore.