## 1 - you will need to edit how your logs look like on Java Format (depending on your logger)
- https://docs.datadoghq.com/logs/log_collection/java/?tab=log4j#raw-format 

## 2 - Add env variable on Application level
```
DD_LOGS_INJECTION=true
```