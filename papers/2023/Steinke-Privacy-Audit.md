# Privacy Auditing with One (1) Training Run

*Skimmed*

## Quick Notes

- They trained one reference model on a randomized set of training examples and performed MIA as a privacy auditing tool
- As DP give us a high-probability upper bound for correct MIA guesses; MIA's correct guesses can imply a high-probability lower bound of DP guarantees
- They mathematically proved that this heuristic (performing MIA on multiple examples simultaneously) is valid using DP and generalization
- They could achieve meaningful privacy empirical lower-bounds applying to the DP-SGD algorithm


## Connections
- Used experimental setup and audit scheme improvements from [Nasr2023](./Nasr-dp-audit.md)
