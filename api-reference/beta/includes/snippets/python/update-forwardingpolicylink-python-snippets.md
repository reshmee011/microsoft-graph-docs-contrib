---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = ForwardingPolicyLink(
	odata_type = "#microsoft.graph.networkaccess.forwardingPolicyLink",
	state = Status.Enabled,
)

result = await graph_client.network_access.forwarding_profiles.by_forwarding_profile_id('forwardingProfile-id').policies.by_policie_id('policyLink-id').patch(body = request_body)


```