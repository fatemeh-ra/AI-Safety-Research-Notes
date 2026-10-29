# Faithfulness

Models have internal computations that results in a final thought and output. How should we understand the internal computations are faithful with the final results and actually reflects the actual thinking process?

- CoT is a window to understand the models reasoning steps and reasoning tree but sometimes we don't have direct access to CoT [3]
- Explicit CoT provides information about the actual reasoning process and steps but it's not always faithful and complete [4]
- Frontier models are moving toward latent CoT that internalize the thinking process [5] we need new mechanisms to understand the internal activations
- Researchers are training "Explainer" models to understand the internal embeddings and explain the reasoning procedure. Some are using the model itself to explain the internal embeddings [1,2]

### Papers
1. [SelfIE: Self-Interpretation of Large Language Model Embeddings](../papers/2024/Chen-SelfIE.md)
1. [Training Language Models to Explain Their Own Computations](../papers/2026/Lin-explaining-computations.md)
1. [Capable yet Parsimonious: Extracting and Characterizing Hidden Chain-of-Thought in Frontier Models](../papers/2026/Luo-CoT-extraction.md)
1. [Chain-of-Thought Is Not Explainability](../papers/2026/Barez-CoT-not-explainability.md)
1. [Does Out-of-Sight Equal Out-of-Mind in CoT Monitorability?](../papers/2026/Ferreira-CoT-mintorability.md)

