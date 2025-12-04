# Simulation Instructions

## Live Endpoints
```
Scheduler API: https://webhook.site/token/https://webhook.site/e376b74d-9cd6-45f4-a6b6-a2359ee5d74a


CMMS API: https://webhook.site/token/https://webhook.site/88d3f9f0-598d-44b4-9f77-94f84688d722
```

## Test Data Generation
Run this curl command to simulate an alert:
```bash
curl -X POST https://webhook.site/token/https://webhook.site/e376b74d-9cd6-45f4-a6b6-a2359ee5d74a
 \
  -H "Content-Type: application/json" \
  -d '{
    "event_id": "test_alert_001",
    "machine_id": "CNC-02",
    "health_score": 65,
    "simulation": true
  }'
```

## n8n Workflow
[![Run in n8n](https://img.shields.io/badge/Run%20in-n8n-blue)](https://joychema.app.n8n.cloud/workflow/SLkPTlbDykknHieV)