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

