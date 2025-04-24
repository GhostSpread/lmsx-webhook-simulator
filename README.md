# LMS Webhook Simulator

Simulate webhook responses for learning management systems to test integrations and event handling.

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"course_id":"CRS123456","event":"course_completed","timestamp":"2025-04-24T14:01:21Z"}'
