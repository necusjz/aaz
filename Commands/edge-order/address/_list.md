# [Command] _edge-order address list_

List all the addresses available under the given resource group. And List all the addresses available under the subscription.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2Vz/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.edgeorder/addresses 2020-12-01-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses 2020-12-01-preview -->

#### examples

- ListAddressesAtResourceGroupLevel
    ```bash
        edge-order address list --resource-group "TestRG"
    ```

- ListAddressesAtSubscriptionLevel
    ```bash
        edge-order address list
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2Vz/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.edgeorder/addresses 2021-12-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses 2021-12-01 -->

#### examples

- ListAddressesAtResourceGroupLevel
    ```bash
        edge-order address list --resource-group "TestRG"
    ```

- ListAddressesAtSubscriptionLevel
    ```bash
        edge-order address list
    ```
