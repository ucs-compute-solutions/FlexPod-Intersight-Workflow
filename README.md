
This repository contains the documentation and JSON files for NetApp workflows to import and use in Cisco Intersight. The documentation for each workflow contains a workflow description, view of the tasks in the workflow, workflow inputs, and an example of workflow execution.

# Workflow Prerequisites

Please check the following relevant prerequisites to ensure that you have met the requirements for running workflows.

- You have gone through your initial FlexPod deployment process by using Ansible Automation or manual deployment by following the relevant Cisco Validated Design (CVD) or NetApp Verified Architecture (NVA) documentation. For more information, please refer to the resources below.
   - [FlexPod Design Guides](https://www.cisco.com/c/en/us/solutions/design-zone/data-center-design-guides/flexpod-design-guides.html)
   - [FlexPod Solutions](https://docs.netapp.com/us-en/flexpod/index.html)

- You have created an Intersight account and deployed Intersight Assist in your environment.

- You have provided Smart Licensing Details in the Licensing settings. You will need Advanced license tier for storage orchestration.

- You have claimed Intersight Assist along with your FlexPod components: Cisco UCS Fabric Interconnects, Cisco Nexus switches, Cisco MDS switches, and NetApp Active IQ Unified Manager with registered NetApp ONTAP storage devices.

- You have downloaded the JSON files for the workflows from this repository and imported them into Cisco Intersight Cloud Orchestrator. Please see the resources below for more information.
   - [Cisco Intersight Help Center information on importing a workflow](https://intersight.com/help/saas/resources/Workflow_Designer#importing_a_workflow)
   - [Workflow import example](WorkflowImport.md)


# Workflows

To locate a NetApp workflow after importing it, you can find it on the My Workflows tab or add a filter for ```Display Name: NetApp```.

To execute a workflow directly, select the **```...```** in the last column of the workflow's row, and then, select **Execute**.
To view the workflow first, click on the workflow link under the Display Name column. Then, you can click the Execute button in the right-hand corner to execute the workflow.

Documentation links for each of the workflows are provided below.

[Add Initiators to NetApp Initiator Group](Add%20Initiators%20to%20NetApp%20Initiator%20Group/AddInitiatorsToNetAppInitiatorGroup.md)

[New Export Policy For NetApp Volume](New%20Export%20Policy%20For%20NetApp%20Volume/NewExportPolicyForNetAppVolume.md)

[New NAS Datastore Using NetApp Smart Volume](New%20NAS%20Datastore%20Using%20NetApp%20Smart%20Volume/NewNASDatastoreUsingNetAppSmartVolume.md)

[New NetApp FC Data Interface](New%20NetApp%20FC%20Data%20Interface/NewNetAppFCDataInterface.md)

[New NetApp Initiator Group](New%20NetApp%20Initiator%20Group/NewNetAppInitiatorGroup.md)

[New NetApp iSCSI Data Interface](New%20NetApp%20iSCSI%20Data%20Interface/NewNetAppiSCSIDataInterface.md)

[New NetApp NAS Data Interface](New%20NetApp%20NAS%20Data%20Interface/NewNetAppNASDataInterface.md)

[New NetApp Storage Virtual Machine](New%20NetApp%20Storage%20Virtual%20Machine/NewNetAppStorageVirtualMachine.md)

[New VMFS Datastore Using NetApp Smart LUN](New%20VMFS%20Datastore%20Using%20NetApp%20Smart%20LUN/NewVMFSDatastoreUsingNetAppSmartLUN.md)

[Remove NAS Datastore Using NetApp Smart Volume](Remove%20NAS%20Datastore%20Using%20NetApp%20Smart%20Volume/RemoveNASDatastoreUsingNetAppSmartVolume.md)

[Remove NetApp Export Policy](Remove%20NetApp%20Export%20Policy/RemoveNetAppExportPolicy.md)

[Remove NetApp Initiator Group](Remove%20NetApp%20Initiator%20Group/RemoveNetAppInitiatorGroup.md)

[Remove VMFS Datastore Using NetApp Smart LUN](Remove%20VMFS%20Datastore%20Using%20NetApp%20Smart%20LUN/RemoveVMFSDatastoreUsingNetAppSmartLUN.md)

[Update NAS Datastore Using NetApp Smart Volume](Update%20NAS%20Datastore%20Using%20NetApp%20Smart%20Volume/UpdateNASDatastoreUsingNetAppSmartVolume.md)

[Update VMFS Datastore Using NetApp Smart LUN](Update%20VMFS%20Datastore%20Using%20NetApp%20Smart%20LUN/UpdateVMFSDatastoreUsingNetAppSmartLUN.md)


On the History tab after executing a workflow, you can use the **Rollback** button to undo the changes that were made by executing the workflow if needed. Also, you can use the **Clone Execution** button to fill in the input parameters using the same values. This is helpful if you want to run the workflow again with only a couple input parameter tweaks.


# Additional Resources
[Cisco Intersight Help Center](https://intersight.com/help/saas)

[Intersight Cloud Orchestrator](https://intersight.com/help/saas/orchestration/configure)

[Workflow Rollback](https://intersight.com/help/saas/orchestration/workflow_rollbacK)