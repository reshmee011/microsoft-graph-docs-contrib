---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = AndroidStoreApp(
	odata_type = "#microsoft.graph.androidStoreApp",
	display_name = "Display Name value",
	description = "Description value",
	publisher = "Publisher value",
	large_icon = MimeContent(
		odata_type = "microsoft.graph.mimeContent",
		type = "Type value",
		value = base64.urlsafe_b64decode("dmFsdWU="),
	),
	is_featured = True,
	privacy_information_url = "https://example.com/privacyInformationUrl/",
	information_url = "https://example.com/informationUrl/",
	owner = "Owner value",
	developer = "Developer value",
	notes = "Notes value",
	publishing_state = MobileAppPublishingState.Processing,
	package_id = "Package Id value",
	app_store_url = "https://example.com/appStoreUrl/",
	minimum_supported_operating_system = AndroidMinimumOperatingSystem(
		odata_type = "microsoft.graph.androidMinimumOperatingSystem",
		v4_0 = True,
		v4_0_3 = True,
		v4_1 = True,
		v4_2 = True,
		v4_3 = True,
		v4_4 = True,
		v5_0 = True,
		v5_1 = True,
		v6_0 = True,
		v7_0 = True,
		v7_1 = True,
		v8_0 = True,
		v8_1 = True,
		v9_0 = True,
		v10_0 = True,
		v11_0 = True,
	),
)

result = await graph_client.device_app_management.mobile_apps.post(body = request_body)


```