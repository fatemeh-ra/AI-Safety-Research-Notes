# SelfIE: Self-Interpretation of Large Language Model Embeddings

*Skimmed*

## Quick Notes
- They enabled LMs to explain their own computations and internal parameters.
- They perform a forward path on a given input computing all internal activations, then they ask the LLM to explain the extracted parameter in another pass. In the second forward pass they patch the actual extracted activation parameter in the chosen layer; bypassing the model computations for that token till that layer.
- Used a relevance score to identify with parts of the explanation is actually generated as the interpretation (not only for the autoregressive nature). They highlighted the explanation examples using the relevance score.
- They proposed to train the model toward providing better explanation with supervised training (minimizing loss toward the better interpretation) or adjusting the RLHF to reward better explanation scored by human or machines. 


## Unclear Points
- Experimental setup details and results are valuable to read
- I still don't understand what do they mean by editing open-ended concepts
