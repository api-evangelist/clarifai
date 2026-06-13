# Clarifai (clarifai)

Clarifai is an AI computer vision and NLP platform providing REST and gRPC APIs for image recognition, object detection, text analysis, visual search, and custom model training. The platform enables teams to build, deploy, and manage AI across shared cloud, on-premise, and edge infrastructure.

**APIs.yml:** [apis.yml](apis.yml)

## APIs

- **Clarifai API** — [Documentation](https://docs.clarifai.com) | [OpenAPI/Swagger](https://api.clarifai.com/api-doc/?url=https://api.clarifai.com/v2/swagger.json)
  - Base URL: `https://api.clarifai.com/v2`
  - Authentication: Personal Access Token (PAT)
  - Protocols: REST (JSON) and gRPC (Protocol Buffers)

## Common Resources

- **Website:** https://www.clarifai.com
- **Documentation:** https://docs.clarifai.com
- **GitHub Org:** https://github.com/Clarifai
- **Blog:** https://www.clarifai.com/blog
- **Pricing:** https://www.clarifai.com/pricing
- **Status Page:** https://status.clarifai.com/
- **LinkedIn:** https://www.linkedin.com/company/clarifai
- **X:** https://x.com/clarifai

## Plans & Pricing

See [plans/clarifai-plans-pricing.yml](plans/clarifai-plans-pricing.yml) for full plan details.

| Plan | Price | Operations/month |
|------|-------|-----------------|
| Community | Free | 1,000 |
| Essential | $30/mo | 30,000 |
| Professional | $300/mo | 100,000 |
| Enterprise | Custom | Unlimited |

## Rate Limits

See [rate-limits/clarifai-rate-limits.yml](rate-limits/clarifai-rate-limits.yml) for details.

- Default: 15 requests per second (all tiers)
- Throttle error: `CONN_THROTTLED` (status 11005)
- Max response size: 128 MB
- Custom limits available for Enterprise (contact sales@clarifai.com)

## FinOps

See [finops/clarifai-finops.yml](finops/clarifai-finops.yml) for cost optimization guidance.

## Tags

AI, Computer Vision, NLP, Image Recognition, Object Detection, Text Analysis, Visual Search, Machine Learning, Custom Model Training, gRPC

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Maintainers

- **Kin Lane** — kin@apievangelist.com
