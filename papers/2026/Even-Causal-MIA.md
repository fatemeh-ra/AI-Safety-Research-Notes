# Causal Evaluation of Membership Inference Attacks

*skimmed*

## Quick Notes

- They evaluated the existing MIAs with causal lens (Not building a new one)
- Redefined different settings of MIA (multi-run, one-run, zero-run) as a causal problem and provided practical solutions to overcome each setup bias (interference between jointly included points in one-run and confounded by distribution shift between member and non-member in zero-run)
- It's specially important for LLM privacy auditing since we are not able to train one or more reference models to perform MIA, and their approach can be a reliable measurement of privacy
