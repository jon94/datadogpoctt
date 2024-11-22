## Choose the correct OS and follow the installation instructions.
- https://app.datadoghq.com/account/settings/agent/latest?platform=overview
- For example Ubuntu replace API_KEY with the correct value.
```
DD_API_KEY=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX \
DD_SITE="datadoghq.com" \
bash -c "$(curl -L https://install.datadoghq.com/scripts/install_script_agent7.sh)"
```

## Log collection
- Activate Log Collection on DD Agent
  - https://docs.datadoghq.com/agent/logs/?tab=tailfiles#activate-log-collection 
- Configure Agent to tail log files
  - https://docs.datadoghq.com/agent/logs/?tab=tailfiles#custom-log-collection

## Useful to troubleshoot permission issues for logs
- https://docs.datadoghq.com/logs/guide/log-collection-troubleshooting-guide/?tab=linux#permission-issues-tailing-log-files