# [Command] _databricks workspace list_

Get all the workspaces.

## Versions

### [2018-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhYnJpY2tzL3dvcmtzcGFjZXM=/2018-04-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.databricks/workspaces 2018-04-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.databricks/workspaces 2018-04-01 -->

#### examples

- List workspaces within a resource group.
    ```bash
        databricks workspace list --resource-group MyResourceGroup
    ```

- List workspaces within the default subscription.
    ```bash
        databricks workspace list
    ```
