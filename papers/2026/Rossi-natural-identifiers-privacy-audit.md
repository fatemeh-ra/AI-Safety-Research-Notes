# Natural Identifiers for Privacy and Data Audits in Large Language Models

*Skimmed*

## Quick Notes

- Uses Natural Identifiers (structured random strings,
such as cryptographic hashes and shortened URLs, etc) to generate non-member examples from the same distribution to audit LLMs
- Zero-run audit without the need to retrain the model, just need some NID in the member dataset; they claim their approach yields to tighter privacy lower-bounds with lower complexity
- Can also be used as Dataset Inference (DI) approach as it's main limitation is requiring a private held-out set from the same distribution. They also introduced a ranking-based test to improve the DI efficiency


## Unclear points
- Have to study the "ranking-based inference" as they claim it to improves the approach flexibility and statistical power


## Connections
- Compares results with the [Steink2023](../2023/Steinke-Privacy-Audit.md) as the one-run baseline
