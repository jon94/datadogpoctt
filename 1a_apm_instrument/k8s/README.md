# Java

- For Java, we can leverage on local library injection using mutatingwebhookconfigurations to ease the set up process. 
- Please refer to the sample_deployment.yaml in this folder on where you should put labels and annotations for library injection to happen.
- For correlation, Datadog relies on tagging. Specifically, something we call unified service tagging - https://docs.datadoghq.com/getting_started/tagging/unified_service_tagging/?tab=kubernetes#containerized-environment
- This can be done directly on the YAML file (see line 5-7, 29-31) in the sample_deployment.yaml in this folder.
- For Datadog webhook to pick up the injection, we will need line 25 and line 27.
- Validation - https://docs.datadoghq.com/tracing/trace_collection/library_injection_local/?tab=kubernetes