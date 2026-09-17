# PANORAMIA: Privacy Auditing of Machine Learning Models without Retraining

*Skimmed*

## Quick Notes

- With a known member set, generates non-member data with a generative model trained on members
- Bypass the limitations of the 1-run privacy audit and estimate the privacy loss of model (but not a lower-bound)without training or changing altering pipeline
- Trains two classifiers; a baseline that only sees members/non-members data and outputs the membership probability, and Panoramia classifier that see data points and their corespondent loss

## Unclear points
- They compute a "c" parameter from the baseline classifier, reflecting the closeness of the data point to member set. It's still unclear how they turned the concept of c-closeness to a privacy bound.


## Connections
- Extended the [Steink2023](../2023/Steinke-Privacy-Audit.md) with generated data as non-members which breaks the data independence assumption

