---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = ApplicationsRequestBuilder.ApplicationsRequestBuilderGetQueryParameters(
		search = "\"displayName:Browser\"",
)

request_configuration = ApplicationsRequestBuilder.ApplicationsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.applications.get(request_configuration = request_configuration)


```