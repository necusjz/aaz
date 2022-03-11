# [Command] _edge-order order-item update_

Update the properties of an existing order item.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcy97fQ==/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems/{} 2020-12-01-preview -->

#### examples

- GetOrderItemByName
    ```bash
        order-item update --name "TestOrderItemName01" --resource-group "TestRG" --contact-details contact-name='Updated contact name'
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvb3JkZXJpdGVtcy97fQ==/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/orderitems/{} 2021-12-01 -->

#### examples

- GetOrderItemByName
    ```bash
        order-item update --name "TestOrderItemName01" --resource-group "TestRG" --contact-details contact-name='Updated contact name'
    ```
