---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new Microsoft.Graph.Beta.Education.Classes.Item.Modules.Item.SetUpResourcesFolder.SetUpResourcesFolderPostRequestBody
{
};
var result = await graphClient.Education.Classes["{educationClass-id}"].Modules["{educationModule-id}"].SetUpResourcesFolder.PostAsync(requestBody);


```