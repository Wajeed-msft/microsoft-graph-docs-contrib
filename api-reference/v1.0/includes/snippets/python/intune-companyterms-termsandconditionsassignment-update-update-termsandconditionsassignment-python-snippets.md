---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = TermsAndConditionsAssignment(
	odata_type = "#microsoft.graph.termsAndConditionsAssignment",
	target = ConfigurationManagerCollectionAssignmentTarget(
		odata_type = "microsoft.graph.configurationManagerCollectionAssignmentTarget",
		collection_id = "Collection Id value",
	),
)

result = await graph_client.device_management.terms_and_conditions.by_terms_and_conditions_id('termsAndConditions-id').assignments.by_terms_and_conditions_assignment_id('termsAndConditionsAssignment-id').patch(request_body)


```