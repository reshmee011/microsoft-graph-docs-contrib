---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


request_configuration = CountRequestBuilder.CountRequestBuilderGetRequestConfiguration(
headers = {
		'ConsistencyLevel' : "eventual",
}

)

await graph_client.groups.by_group_id('group-id').members.count.get(request_configuration = request_configuration)


```