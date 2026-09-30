# Did the Neurons Read your Book? Document-level Membership Inference for Large Language Models

*Skimmed*

## Quick Notes
- Developed a zero-run auditing schema to check a document (book, paper) is used as a training source for the LLM
- Proposed to use similar public documents made available after LLM release as non-members
- Queries the LM to obtain model confidence on next token -> normalize confidence based on token rarity (multiple approaches: token frequency, general probability and difference between true token vs max probability) -> aggregate the normalized confidence to compute a single score for each document (AggFE and HistFE) -> train a meta classifier
