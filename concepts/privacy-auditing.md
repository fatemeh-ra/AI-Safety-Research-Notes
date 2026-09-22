# Privacy Auditing

For a given model regardless of the used training safe-guards we need a tool to audit the privacy preservation. Membership inference attack can be used here as a tool to quantify privacy leakage and also provide empirical lower-bounds for DP.

**Approaches:**

1. Multi-run: Using classic MIA, training several (hundreds to thousands) reference models per example
2. One-run: Training only one reference model on a randomized set of examples [1]
3. Zero-run: Audit without training any reference models. Used when training a reference model is not feasible (e.g., LLM privacy auditing) [2,4,5,7]


### Papers
1. [Privacy Auditing with One (1) Training Run](../papers/2023/Steinke-Privacy-Audit.md)
1. [Privacy Auditing with Zero (0) Training Run](../papers/2026/Cebere-zero-run-audit.md)
1. [Causal Evaluation of Membership Inference Attacks](../papers/2026/Even-Causal-MIA.md)
1. [PANORAMIA: Privacy Auditing of Machine Learning Models without Retraining](../papers/2024/Kazmi_panoramia.md)
1. [Natural Identifiers for Privacy and Data Audits in Large Language Models](../papers/2026/Rossi-natural-identifiers-privacy-audit.md)
1. [Tight auditing of differentially private machine learning](../papers/2023/Nasr-dp-audit.md)
1. [Scalable membership inference attacks via quantile regression](../papers/2023/Betran_mia.md)
