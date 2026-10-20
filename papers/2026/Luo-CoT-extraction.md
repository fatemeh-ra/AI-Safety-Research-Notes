# Capable yet Parsimonious: Extracting and Characterizing Hidden Chain-of-Thought in Frontier Models

*Skimmed*

## Quick Notes
- They forced the model to externalize the thoughts, even when the actual CoT is unavailable.
- Using the API’s tool-choice control, forced the model to pass reasoning to a defined function. They evaluated this simple technique by comparing the extracted text with the actual CoT of some models. However, we can not be sure the extracted text is the model’s actual internal reasoning
- Illustrated the reasoning tree for different models, Astra has the most straight forward reasoning path and internalize most initial reasoning. It's the most efficient model in terms of reasoning-token usage.


## Connections
- Considering [Barez2026](./Barez-chain-of-thought.md), is CoT a useful tool to build the reasoning tree? How can we consider internalized thoughts?
- [Barez2026](./Barez-chain-of-thought.md) suggested to evaluate the CoT with causal validation methods, but Astra and probably other frontier models internalize most initial reasoning, then how can we evaluate their alignment and faithfulness of their thoughts?


