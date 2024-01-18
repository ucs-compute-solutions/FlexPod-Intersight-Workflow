# Add Initiators to NetApp Initiator Group Workflow

## Workflow description and tasks

The Add Initiators to NetApp Initiator Group workflow adds one or more
initiators to an existing initiator group.

![](../images/AddInitiatorsToNetAppInitiatorGroup/0bd6a3214cb0d979e5d82414b584af2d6532c62b.png)

## Workflow inputs
\* indicates the input is required

- **Storage Device\***

- **Storage Virtual Machine\***

- **Initiator Group\***

- **Initiators:** The initiators to add to the initiator group. Use Fibre
Channel (FC) world wide port names (WWPNs), iSCSI qualified names
(IQNs), and/or iSCSI extended unique identifiers (EUIs) to identify host
initiators.

## Example workflow execution

1.  Select the storage device, storage virtual machine, and initiator
    group.

![](../images/AddInitiatorsToNetAppInitiatorGroup/30a1b9262681dde0e5499f94cfd39fbaf4fb43d2.png)

![](../images/AddInitiatorsToNetAppInitiatorGroup/dd926ee4f85b475f2956e91203c5f69471da1f7c.png)

![](../images/AddInitiatorsToNetAppInitiatorGroup/a93128a6ca6c2a895cf9b131cac470bedc2ec410.png)

2.  Provide the initiator(s) to add to the initiator group.

![](../images/AddInitiatorsToNetAppInitiatorGroup/b84bb8bbe386865f4adc4fea78d007051cf1e476.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/AddInitiatorsToNetAppInitiatorGroup/caa01ea1e0dc4f6ad8fd7af956344f366fa62a0c.png)

**NOTE:** There is no Rollback available for this workflow. If you need to
undo this workflow execution, please use the Remove Initiators from
NetApp Initiator Group workflow.