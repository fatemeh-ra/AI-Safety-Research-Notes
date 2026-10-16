# Benchmarking Membership Privacy Risks in Preference-Based LLM Post-Training

*Skimmed*

## Quick Notes
- Extracting membership signals from the preferences used in the LLM post-training
- Used 4 scores: preferred-response, dispreferred-response, scalar preference-margin (compressed version of how model prefers the response) and signed response-pair (signed contrast between responses); The latest is the most powerful one
- Used reference-based MIA attack with 4 references with each setting
- Evaluate post-training algorithms: SFT, DPO-based methods (DPO, IPO, ORPO, KTO) and RL-based methods (PPO and GRPO)

