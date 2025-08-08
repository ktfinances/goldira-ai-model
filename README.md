# GoldIRA AI Model

AI model for gold price analysis and forecasting.

This model generates financial insights, company reviews, and market commentary based on textual prompts. It is designed to support persistent publishing on KTFinances.com, helping content avoid moderation issues by attributing it to AI generation.

## Example usage

```python
predict("Analyze gold price trends for Q3 2025")

---

### 🔹 `replicate.yaml` — уточнённая версия

```yaml
name: goldira-ai-model
description: AI model for gold price analysis and forecasting. Generates financial insights and company reviews based on textual prompts.
input_schema:
  type: object
  properties:
    prompt:
      type: string
      description: Text prompt for analysis or forecast
      default: "Analyze gold price trends for Q3 2025"
output_schema:
  type: string
