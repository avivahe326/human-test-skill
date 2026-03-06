# human-test-skill

Real human usability testing as an agent skill. Get structured feedback with NPS scores, screen recordings, and AI-aggregated reports for any product URL.

## Install

```bash
npx skills add avivahe326/human-test-skill
```

## What it does

1. Call the API with a product URL
2. AI auto-generates a test plan
3. Real humans test your product with screen recording + audio
4. AI analyzes recordings and aggregates feedback into a structured report

## Quick start

Register at [human-test.work](https://human-test.work/register) for a free API key (100 credits on signup).

```bash
curl -X POST https://human-test.work/api/skill/human-test \
  -H "Authorization: Bearer <your-api-key>" \
  -H "Content-Type: application/json" \
  -d '{"url": "https://your-product.com", "focus": "Test the onboarding flow"}'
```

See the full [SKILL.md](skills/human-test/SKILL.md) for all parameters and details.
