# Protecting against simultaneous data poisoning attacks

*Skimmed*

## Quick Notes
- Previous defenses focused on detecting a single backdoor, while a model can have multiple data poisoning backdoor all at once with clean accuracy in typical tasks
- Focused on data poisoning attacks in images and assumes the defender has access to a set of clean examples
- Method:
    1. Computes the "loss trajectory" of clean samples by building a vector of its loss over the training epoch
    2. Do the same for other samples and compare their loss trajectory with known clean samples, assigning a score as the probability of the example being backdoored
    3. Remove high probable backdoored examples from the training set and retrain from the scratch
