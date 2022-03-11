# [Command] _edge-order address create_

Create a new address with the specified parameters. Existing address can be updated with this API.

## Versions

### [2020-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2VzL3t9/2020-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses/{} 2020-12-01-preview -->

#### examples

- CreateAddress
    ```bash
        edge-order address create --name "TestMSAddressName" --location "eastus" --contact-details {contact-name:'Petr Cech',email-list:testemail@microsoft.com,phone:1234567890,phone-extension:} --shipping-address {address-type:'None',city:'San Francisco',company-name:Microsoft,country:US,postal-code:94107,state-or-province:CA,street-address1:'16 TOWNSEND ST',street-address2:'UNIT 1'} --resource-group TestRG
    ```

### [2021-12-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lZGdlb3JkZXIvYWRkcmVzc2VzL3t9/2021-12-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.edgeorder/addresses/{} 2021-12-01 -->

#### examples

- CreateAddress
    ```bash
        edge-order address create --name "TestMSAddressName" --location "eastus" --contact-details {contact-name:'Petr Cech',email-list:testemail@microsoft.com,phone:1234567890,phone-extension:} --shipping-address {address-type:'None',city:'San Francisco',company-name:Microsoft,country:US,postal-code:94107,state-or-province:CA,street-address1:'16 TOWNSEND ST',street-address2:'UNIT 1'} --resource-group TestRG
    ```
