# Remove Initiators from NetApp Initiator Group Workflow

## Workflow description and tasks

The Remove Initiators from NetApp Initiator Group workflow removes one
or more initiators from an existing initiator group. The Remove
Initiator from NetApp Initiator Group task is run in parallel for each
initiator provided. The order of completion may differ from the order
that the initiators were given due to parallel execution.

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/87f7c33d4f670c239243cb5c5359261bd44becec.png)

## Workflow inputs
\* indicates the input is required

**Storage Device\***

**Storage Virtual Machine\***

**Initiator Group\***

**Initiators\*:** The initiators to add to the initiator group. Use
Fibre Channel (FC) world wide port names (WWPNs), iSCSI qualified names
(IQNs), and/or iSCSI extended unique identifiers (EUIs) to identify host
initiators.

## Example workflow execution

1.  Select the storage device, storage virtual machine, and initiator
    group.

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/90dc399705544e06c38bddf6ab9b850a437d74d1.png)

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/412f4c11d095695525aaf36d5989d8fb8e89beb3.png)

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/c7d72a6fd9d48965e19f73f1e7b8306872955a77.png)

2.  Provide the initiator(s) to remove from the initiator group.

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/36266b9512979d9e2e72dc0a1b054b3dbe7807a7.png)

3.  Review your input selections for correctness, then click **Execute**.

4.  View workflow execution details on the History tab.

![](../images/RemoveInitiatorsFromNetAppInitiatorGroup/930b6a5ee0fbe1603d27dc1c9e36320447836041.png)

**NOTE:** There is no Rollback available for this workflow. If you need to
undo this workflow execution, please use the Add Initiators to NetApp
Initiator Group workflow.
