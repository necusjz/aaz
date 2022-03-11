# [Command] _edge-order order-item cancel_

Cancel order item.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcy97fS9jYW5jZWw=/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems/{}/cancel 2020-12-01-preview -->

#### examples

- CancelOrderItem
    ```bash
        edge-order order-item cancel --reason "Order cancelled" --name "TestOrderItemName1" --resource-group "TestRG"
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcy97fS9jYW5jZWw=/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems/{}/cancel 2021-12-01 -->

#### examples

- CancelOrderItem
    ```bash
        edge-order order-item cancel --reason "Order cancelled" --name "TestOrderItemName1" --resource-group "TestRG"
    ```
