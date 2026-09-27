# Scalable Extraction of Training Data from (Production) Language Models

*Skimmed*

# Quick Notes
- They could extensively extract training data from large-scale production LMs by querying without prior knowledge about the training set
- Developed a divergence attack on chat-gpt-3.5 turbo that caused it to diverge from the reasonable, chat-style generation and to emit training data points at a rate of 150x higher
- Defined "Extractable Memorization" and "Discoverable Memorization"

## Unclear Points
- Too many useful details that I have to read more carefully, especially on divergence attack and why it only works on gpt-family
- How do they evaluated alignment techniques not helping in memorization
- How data deduplication affect the memorization and data emission? Did future works covered this question?
- Is it fair to say the  capacity is "wasted" on the verbatim memorization? Where did "approximately 10% capacity waste" comes from?
