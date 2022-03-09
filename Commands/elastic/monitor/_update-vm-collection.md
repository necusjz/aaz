# [Command] _elastic monitor update-vm-collection_

Update the vm details that will be monitored by the Elastic monitor resource.

## Versions

### [2020-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lbGFzdGljL21vbml0b3JzL3t9L3ZtY29sbGVjdGlvbnVwZGF0ZQ==/2020-07-01.xml) **Experimental**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.elastic/monitors/{}/vmcollectionupdate 2020-07-01 -->

#### examples

- VMCollection Update
    ```bash
        elastic monitor update-vm-collection --name myMonitor --resource-group myResourceGroup --operation-name Add --vm-resource-id /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myResourceGroup/providers/Microsoft.Compute/virtualmachines/myVM
    ```
