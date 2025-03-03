# [Command] _workloads sap-application-server-instance stop_

Stops the SAP Application Server Instance.

## Versions

### [2023-04-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC53b3JrbG9hZHMvc2FwdmlydHVhbGluc3RhbmNlcy97fS9hcHBsaWNhdGlvbmluc3RhbmNlcy97fS9zdG9w/2023-04-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.workloads/sapvirtualinstances/{}/applicationinstances/{}/stop 2023-04-01 -->

#### examples

- Stop Application server instance of the SAP system
    ```bash
        workloads sap-application-server-instance stop --sap-virtual-instance-name <VIS Name> -g <Resource-group-name> -n <ResourceName>
    ```

- Stop Application server instance of the SAP system using the Azure resource ID of the instance
    ```bash
        workloads sap-application-server-instance stop --id <ResourceID>
    ```
