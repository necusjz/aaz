# [Command] _data-bricks workspace vnet-peering create_

Create a vnet peering for a workspace.

## Versions

### [2018-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhYnJpY2tzL3dvcmtzcGFjZXMve30vdmlydHVhbG5ldHdvcmtwZWVyaW5ncy97fQ==/2018-04-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.databricks/workspaces/{}/virtualnetworkpeerings/{} 2018-04-01 -->

#### examples

- Create a vnet peering for a workspace
    ```bash
        data-bricks workspace vnet-peering create --resource-group MyResourceGroup --workspace-name MyWorkspace -n MyPeering --remote-vnet /subscriptions/000000-0000-0000/resourceGroups/MyRG/providers/Microsoft.Network/virtualNetworks/MyVNet
    ```

### [2021-04-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhYnJpY2tzL3dvcmtzcGFjZXMve30vdmlydHVhbG5ldHdvcmtwZWVyaW5ncy97fQ==/2021-04-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.databricks/workspaces/{}/virtualnetworkpeerings/{} 2021-04-01-preview -->

#### examples

- Create a vnet peering for a workspace
    ```bash
        data-bricks workspace vnet-peering create --resource-group MyResourceGroup --workspace-name MyWorkspace -n MyPeering --remote-vnet /subscriptions/000000-0000-0000/resourceGroups/MyRG/providers/Microsoft.Network/virtualNetworks/MyVNet
    ```
