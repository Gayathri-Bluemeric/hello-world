runbook-4
**Prometheus Alert [Kubernetes aggregated API server is down]**
```yaml
labels:
  alertname: KubeAggregatedAPIDown
  severity: critical
annotations:
  description: The Kubernetes aggregated API server has been down for more than 5 minutes.
  summary: Kubernetes aggregated API server is down
state: firing
activeAt: '[REDACTED_TIMESTAMP_ISO8601]'
value: '1e+00'
selected: true
```
