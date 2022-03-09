# [Command] _elastic monitor tag-rule show_

Get a tag rule set for a given monitor resource.

## Versions

### [2020-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lbGFzdGljL21vbml0b3JzL3t9L3RhZ3J1bGVzL3t9/2020-07-01.xml) **Experimental**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.elastic/monitors/{}/tagrules/{} 2020-07-01 -->

#### examples

- TagRules Get
    ```bash
        elastic monitor tag-rule show --monitor-name myMonitor --resource-group myResourceGroup --rule-set-name default
    ```
