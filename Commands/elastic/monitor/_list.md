# [Command] _elastic monitor list_

List all monitors under the specified resource group. And List all monitors under the specified subscription.

## Versions

### [2020-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lbGFzdGljL21vbml0b3Jz/2020-07-01.xml) **Experimental**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.elastic/monitors 2020-07-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.elastic/monitors 2020-07-01 -->

#### examples

- Monitors List By ResourceGroup
    ```bash
        elastic monitor list --resource-group myResourceGroup
    ```

- Monitors List
    ```bash
        elastic monitor list
    ```
