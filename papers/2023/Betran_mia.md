# Scalable membership inference attacks via quantile regression

*Skimmed*

## Quick Notes
- Introduced a new MIA comparable to LiRA without training reference models using only a single quantile regression model (black-box zero-run attack)
- The attack is a likelihood ratio test with only one null hypothesis; a data point was not used in training
- The quantile regression model is trained using an $\alpha$ parameter that will be the false-positive rate of the attack by design, so to observe the tradeoff between false positive and true positive rates we have to train multiple quantile regression models with sweeping $\alpha$ values


