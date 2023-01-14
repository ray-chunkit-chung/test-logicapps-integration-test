# LogicApps unit test getting started

Modify from
https://www.integration-playbook.io/docs/logic-app-testing
https://coffeefirst.dev/azure/how-to-test-a-logic-app/
https://www.mikestephenson.me/2021/12/11/logic-app-standard-integration-testing/

## Prerequisite

1. Install Dotnet SDK https://dotnet.microsoft.com/en-us/download/visual-studio-sdks

## Setup
```
dotnet new sln
dotnet sln add LogicApp.Testing.Example/LogicApp.Testing.Example.csproj
dotnet add package IPB.LogicApp.Standard.Testing --version 1.0.690

```


# Parameters
 - ClientID = a client id for an Azure AD app registration which you have set up
 - ClientSecret = The secret for your azure ad app registration
 - TenantId = The tenant id for your azure ad
 - LogicAppName = The logic app name in Azure
 - ResourceGroupName = The resource group that the logic app lives in
 - SubscriptionId = The subscription id the logic app lives in
 - WorkflowName = The name of the workflow within the logic app you want to test


