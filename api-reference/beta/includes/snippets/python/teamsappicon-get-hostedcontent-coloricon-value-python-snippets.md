---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


result = await graph_client.app_catalogs.team_apps.by_team_app_id('teamsApp-id').app_definitions.by_app_definition_id('teamsAppDefinition-id').color_icon.hosted_content.get()


```