---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = SmsAuthenticationMethodConfiguration(
	odata_type = "#microsoft.graph.smsAuthenticationMethodConfiguration",
	id = "Sms",
	state = AuthenticationMethodState.Enabled,
)

result = await graph_client.policies.authentication_method_policy.authentication_method_configurations.by_authentication_method_configuration_id('authenticationMethodConfiguration-id').patch(body = request_body)


```