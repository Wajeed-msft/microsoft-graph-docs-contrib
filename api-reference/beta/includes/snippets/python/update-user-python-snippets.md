---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = User(
	business_phones = [
		"+1 425 555 0109",
	],
	office_location = "18/2111",
)

result = await graph_client.me.patch(request_body)


```