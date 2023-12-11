# Remove VMFS Datastore Using NetApp Smart LUN Workflow

## Workflow description and tasks

The Remove VMFS Datastore Using NetApp Smart LUN workflow removes a VMFS
datastore and the underlying storage volume and LUN using the Remove
NetApp Smart LUN task. When a datastore is removed from a host, it is
destroyed and will disappear from all hosts that have access to it. If a
cluster name is provided, the datastore is removed from all hosts in the
cluster.

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/9ec006cd24178f4d409298ad8916bb0b70fbf534.png)

## Workflow inputs
\* indicates the input is required

### Hypervisor inputs:

**Hypervisor Manager\*:** Hypervisor manager managing the cluster in the
datacenter.

**Datacenter\*:** Datacenter associated with the cluster where the
datastore is hosted.

**Cluster:** Cluster on which the datastore will be hosted.

**Host:** Host on which the datastore will be hosted. If the cluster is
specified, the host parameter will be ignored.

**Datastore\*:** Name of the datastore for which capacity is to be
expanded

### Storage inputs:

**Storage Device\***

## Example workflow execution

1.  Select the hypervisor manager, datacenter, cluster or host, and the
    datastore that is to be removed.

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/905ac6d7b521f9a48b4c8745c468a834b44e424a.png)![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/6edd5f9494b55accf15a5d47721b379bd55ba213.png)

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/f3e57536048066444f7eca5c3cc3a2d86d23a307.png)![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/d3410d85cb133ec2122d4ef708e732602b3fdde8.png)

2.  Select the storage device.

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/abad1cf55c7b2343d8320183f6b4e1cd0d48f659.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/7bbe0368f099993572a5c241dacdd906252eae86.png)

![](../images/RemoveVMFSDatastoreUsingNetAppSmartLUN/35fda4157bcdf8a6fc49fec3bf4e386569cadef7.png)
