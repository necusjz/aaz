# [Command] _edge-order order-item list_

List order at resource group level. And List order at subscription level.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcw==/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.edgeorder/orderitems 2020-12-01-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems 2020-12-01-preview -->

#### examples

- ListOrderAtResourceGroupLevel
    ```bash
        edge-order order list --resource-group "TestRG"
    ```

- ListOrderItemsAtSubscriptionLevel
    ```bash
        edge-order order-item list
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcw==/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.edgeorder/orderitems 2021-12-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems 2021-12-01 -->

#### examples

- ListOrderAtResourceGroupLevel
    ```bash
        edge-order order list --resource-group "TestRG"
    ```

- ListOrderItemsAtSubscriptionLevel
    ```bash
        edge-order order-item list
    ```
