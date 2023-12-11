#  New VMFS Datastore Using NetApp Smart LUN Workflow

## Workflow description and tasks

The New VMFS Datastore Using NetApp Smart LUN workflow creates a new
VMFS datastore. A volume and LUN with the same name as the datastore are
created using the New NetApp Smart LUN task.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/0e5933ef3d08b0368b5125e4af5a9813f397512f.png)

## Workflow inputs
\* indicates the input is required

### Hypervisor inputs:

**Hypervisor Manager\*:** Hypervisor manager managing the cluster in the
datacenter.

**Datacenter\*:** Datacenter associated with the cluster where the
datastore will be hosted.

**Cluster:** Cluster on which the datastore will be hosted.

**Host:** Host on which the datastore will be hosted. If the cluster is
specified, the host parameter will be ignored.

**Datastore Name\*:** Name of the datastore. The volume and LUN created
will be named the same as the datastore name and the LUN path will be at
/vol/datastore_name/datastore_name.

**Datastore Capacity\*:** Size of the datastore

**Datastore Type\*:** Type of the datastore (VMFS version 5 or 6)

### Storage inputs:

**Storage Device\***

**Storage Virtual Machine\***

**Performance Service Level\*:** Performance service levels represent
the performance expectations of the clients or applications using the
storage system. The selection of a performance service level indicates
the location of the new storage in the storage device and the QoS policy
assigned to the storage. Value is used for applications for which
throughput and capacity are more important than latency. Performance is
used for applications with modest performance needs and latency. Extreme
is used for applications that expect the lowest latency and highest
performance. **NOTE:** If the selected performance service level is not
valid for the storage platform, the task will fail with an error
message. Use the 'None' option if the storage virtual machine already
has a QoS policy group.

**Initiator Group\***: You can select an initiator group or create a new
one. If you create a new initiator group, you need to provide the
following inputs.

-   **Initiator Group Name\*:** The name of the initiator group.

-   **Operating System\*:** The host operating system of the initiator
    group. All initiators in the group should be hosts of the same
    operating system.

-   **Protocol:** The protocol(s) supported by the initiator group
    (iSCSI, FCP, or Mixed).

-   **Initiators\*:** The initiator(s) to add to the new initiator
    group. Use Fibre Channel (FC) world wide port names (WWPNs), iSCSI
    qualified names (IQNs), and/or iSCSI extended unique identifiers
    (EUIs) to identify host initiators.

**Enable Local Snapshot Copies:** Select this checkbox to enable local
snapshot copies using the default snapshot policy.

## Example workflow execution

1.  Select the hypervisor manager, datacenter, and cluster where the
    datastore will be created. Leave the host unselected to mount the
    new datastore on all the hosts. To mount the new datastore on a
    single host, select the host, but not the cluster.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/bbef819a399c6c2825f8bb1202e2833ffb49376f.png)

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/02ab6352fd125d3d270076a6907838384e4cb6d9.png)

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/90ddc35761045c4c0d0159eff2ad4f65269f5e30.png)

2.  Provide the desired datastore name and capacity. Select the
    datastore type.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/135d92dceab7546dcf69f91e6daf62fe03ecb935.png)

3.  Select storage device, storage virtual machine, and performance
    service level. **NOTE:** If the selected performance service level is
    not valid for the storage platform, the task will fail with an error
    message.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/080663d027d43ffa877c76ecb564e52b526238a8.png)

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/48c9bde4a6184ff3699f63dd9c71ca3360099d5c.png)

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/0396cfc8547c6f4252328e278491b10d1feab785.png)

4.  Either select an existing initiator group or create a new initiator
    group. The example below selects an existing initiator group. To
    create a new initiator group instead, select 'New Initiator Group',
    then provide the initiator group name, operating system, protocol,
    and initiator(s).

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/1a0bf828040cc6d01d77d36f4fc3cbcb9bcb0ce3.png)

5.  Enable local snapshot copies as needed.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/1676fff1ec5edd9d3fffe73d3d79ee3d69348808.png)

6.  Review your input selections for correctness, then click **Execute**.

7.  View workflow execution details on the History tab.

![](../images/NewVMFSDatastoreUsingNetAppSmartLUN/313d1fdfddc546ac6f3a89edaeed825cf31d4ecb.png)
