---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = ChatsRequestBuilder.ChatsRequestBuilderGetQueryParameters(
		expand = ["lastMessagePreview"],
)

request_configuration = ChatsRequestBuilder.ChatsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.chats.get(request_configuration = request_configuration)


```