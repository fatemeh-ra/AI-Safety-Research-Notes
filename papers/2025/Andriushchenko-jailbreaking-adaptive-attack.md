# Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks

*Skimmed*

## Quick Notes
- Introduced an adaptive method for jailbreaking attacks, they start with a prompt template and then optimize the attack success rate with a random search algorithm on a suffix (e.g., "Sure") to maximize the logprob
- They achieved almost 100% attack success rate on all tested models
- Introduced Self-transfer as an attack optimization technique to use the adversarial suffix for a simpler task as the initialization data for random search on a harder challenge
- They used transfer attacks (to use the same adversarial prefix computed for other models) and prefilling attacks (to prefill the response to initialize a target behavior) to attack Claude as it does not expose logprobs making the random search not applicable
- Also used same method to detect trojan strings in poisoned models with random search and restricting the search space by applying the prior knowledge 

