# Chain-of-Thought Is Not Explainability

*Skimmed*

- Chain-of-thought is being used as an trusted interpretability tool in high-stake real-world use-cases and this paper argues that it's not faithful and trustworthy enough for such scenarios
- There are examples where the CoT provide an unfaithful explanation like, different answers when a multi-choice question is reordered or an error in intermediate reasoning steps while the final answer is correct (it silently fixed the error or never used the intermediate reasoning)
- They claim that unfaithfulness is not a rare observation but a recurring phenomenon with certain patterns
