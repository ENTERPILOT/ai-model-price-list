# AI Model Price List

Auto-updated AI/LLM model pricing data aggregated from multiple public sources.

Fetched every 6 hours via GitHub Actions.

## Sources

All pricing data is stored in the `sources/` directory.

| File | Source | Prices Unit | License |
|---|---|---|---|
| `sources/litellm_model_prices.json` | [LiteLLM](https://github.com/BerriAI/litellm) | USD per token | MIT |
| `sources/portkey/*.json` | [Portkey-AI](https://github.com/Portkey-AI/models) | Cents per token | MIT |
| `sources/pydantic_genai_prices.json` | [pydantic/genai-prices](https://github.com/pydantic/genai-prices) | USD per token | MIT |
| `sources/openrouter_models.json` | [OpenRouter](https://openrouter.ai/docs) | USD per token (string) | Unspecified |
| `sources/llm_prices_current.json` | [llm-prices](https://github.com/simonw/llm-prices) | USD per million tokens | Unspecified |

## Usage

Fetch the raw files directly from this repo, e.g.:

```
https://raw.githubusercontent.com/ENTERPILOT/ai-model-price-list/main/sources/litellm_model_prices.json
```
