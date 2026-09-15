# Privacy Auditing

For a given model regardless of the used training safe-guards we need a tool to audit the privacy preservation. Membership inference attack can be used here as a tool to quantify privacy leakage and also provide empirical lower-bounds for DP.

**Approaches:**

1. Multi-run: Using classic MIA, training several (hundreds to thousands) reference models per example
2. One-run: Training only one reference model on a randomized set of examples [1].
3. Zero-run: Audit without training any reference models. Used when training a reference model is not feasible (e.g., LLM privacy auditing)


### Papers
1. [Privacy Auditing with One (1) Training Run](../papers/2023/Steinke-Privacy-Audit.md)
2. [Causal Evaluation of Membership Inference Attacks](../papers/2026/Even-Causal-MIA.md)
