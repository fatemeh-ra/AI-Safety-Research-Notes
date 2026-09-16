# Privacy Auditing with Zero (0) Training Run

*Skimmed*

## Quick Notes
- Provide DP-lower bounds post-hoc training, just based on a known set of members and non-members
- As the members, non-members sets may have sampled from different distributions, they used a propensity score scheme to debias the distribution shift
- The propensity score is selected conservatively; overestimating the overlap can invalidate the audit but underestimating it result in an conservative lower-bound (attributes more signal to distribution shift)

## Unclear points
- I still don't understand the difference between the first and second privacy correction approaches; Composition Viewpoint vs Conditional Viewpoint
- What about the member outliers? Can conservative propensity score dilute the privacy leakage?

## Connections
- Used propensity score introduced in [Even2026](../2026/Even-Causal-MIA.md) to debias the distribution shift and calibrate the MIA
- DP lower bounds are calculated similar to [Steinke2023](../2023/Steinke-Privacy-Audit.md), here for 0-run auditing