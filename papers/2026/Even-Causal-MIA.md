# Causal Evaluation of Membership Inference Attacks

*read*

## Quick Notes

- They evaluated the existing MIAs with causal lens (Not building a new one)
- Redefined different settings of MIA (multi-run, one-run, zero-run) as a causal problem and provided practical solutions to overcome each setup bias; interference between jointly included points in one-run and confounded by distribution shift between member and non-member in zero-run
- Trained a simple binary classifier to debias the MIA evaluations in zero-run regime using a propensity score

## Detailed Notes

**Evaluation Metrics:**
- Membership advantage -- causal --> Average Treatment Effect
- AUC -- causal --> Causal AUC
- TPR @ FPR -- causal --> Causal TPR @ FPR

**Causal Interpretation**
- multi-run: The RCT randomized assumption is hold --> No correction needed
- one-run: Use RCT with interference (Other existing points can interfere results with the selected sample) --> With a stability assumption on training algorithm we can use the traditional MIA
- zero-run: Turns it to observational study with interference --> Introduces a propensity score (inverse probability weighting (IPW) estimator) to debias the distribution shifts. Propensity score can be simply derived from any probabilistic binary classifier trained on members/non-members


**Limitation**
- Used membership advantage in theorems and proofs but evaluated the corrected MIA via AUC score
- What about the TPR @ low FPR evaluations?
- Used only loss as the MIA score, is there any membership score available?
- I can not understand the stability parameter used in one-run regime evaluations. In privacy auditing we don't have access to training algorithm so the stability assumption can not be verified, and there is no correction algorithm introduced for this regime to debias the interference.

