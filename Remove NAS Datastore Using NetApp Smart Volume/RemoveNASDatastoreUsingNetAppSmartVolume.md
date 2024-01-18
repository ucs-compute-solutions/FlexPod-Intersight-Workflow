# Remove NAS Datastore Using NetApp Smart Volume Workflow

## Workflow description and tasks

The Remove NAS Datastore Using NetApp Smart Volume workflow removes a NAS datastore from all hosts in the cluster. The underlying storage volume is removed using the Remove NetApp NAS Smart Volume task.

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/4b6d05d1bc4c0468c2f1bde9c98a4576db0af9d6.png)

## Workflow inputs
\* indicates the input is required

### Hypervisor inputs:

- **Hypervisor Manager\*:** Hypervisor manager managing the cluster in the
datacenter.

- **Datacenter\*:** Datacenter associated with the cluster where the
datastore is hosted.

- **Cluster\*:** Cluster on which the datastore is hosted.

- **Datastore\*:** Name of the datastore to be removed.

### Storage inputs:

- **Storage Device\***

## Example workflow execution

1.  Select the hypervisor manager, datacenter, cluster or host, and the
    datastore that is to be removed.

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/38a3c5aac483c3df44be550d958594251ccc6a0c.png)

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/8beccebe79d4ee983a54527ef8587987305354d9.png)

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/6a97140c9dc1ccec3cffb09008639a84f5f134b5.png)

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/7e7ddd8ed0bf68c9116dc39913f1090885787f12.png)

2.  Select the storage device.

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/bb3925c8ab6a60cffcf2057b46ff123042fe9b0d.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/RemoveNASDatastoreUsingNetAppSmartVolume/29ee8ea2ef0e4355c8cf6a8954d4b496b7787435.png)