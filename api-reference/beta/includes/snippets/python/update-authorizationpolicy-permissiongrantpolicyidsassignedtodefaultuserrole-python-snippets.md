---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = AuthorizationPolicy(
	permission_grant_policy_ids_assigned_to_default_user_role = [
		"managePermissionGrantsForSelf.microsoft-user-default-low",
	]
)

result = await graph_client.policies.authorization_policy.by_authorization_policy_id('authorizationPolicy-id').patch(body = request_body)


```