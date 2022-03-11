# [Command] _edge-order address update_

Update the properties of an existing address.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2VzL3t9/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses/{} 2020-12-01-preview -->

#### examples

- UpdateAddress
    ```bash
        edge-order address update --name "TestMSAddressName" --location "eastus" --resource-group TestRG --contact-details contact-name='Petr Cech'
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2VzL3t9/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses/{} 2021-12-01 -->

#### examples

- UpdateAddress
    ```bash
        edge-order address update --name "TestMSAddressName" --location "eastus" --resource-group TestRG --contact-details contact-name='Petr Cech'
    ```
