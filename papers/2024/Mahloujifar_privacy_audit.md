# Auditing f -Differential Privacy in One Run

*Skimmed*

## Quick Notes
- Achieves a tight empirical privacy estimates with only one-run training using the randomness of training points
- They bounded the adversary correct guesses (forming a random variable) with a recursive approach conditional on the correct/incorrect guesses
- It's not a strict privacy guarantee, it's a practical estimation of privacy parameters. However, there is still a gap between empirical bound and theoretical privacy in one-run regime

## Connections
- Improves the one-run privacy audit introduced by [Steinke2023](../2023/Steinke-Privacy-Audit.md). Steinke bounded the tail of correct guess random variable with a binomial distribution, they extended this to provide a tighter bound.
