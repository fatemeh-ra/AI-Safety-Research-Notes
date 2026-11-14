# Be like a Goldfish, Don’t Memorize! Mitigating Memorization in Generative LLMs

*Skimmed*

## Quick Notes
- Masks some tokens in backward pass to prevent the LLM memorize the exact verbatim sequence
- As the model observe all tokens in the forward pass, the performance remains comparable. Although we may need more training runs to cover the effects of excluded tokens
- They use a hashed mask, the mask is computed based on the hash value of a context window. With this design a duplicate training point always have the same mask parameters
- The hashed mask is an advantage against methods like differential privacy as it generate identical masks for duplicate examples but DP mechanisms fails when a document appears many times

