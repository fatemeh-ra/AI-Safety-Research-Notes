# The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against Llm Jailbreaks and Prompt Injections

*Skimmed*

## Quick Notes
- Designed attacks to bypass the jail-breaking and prompt injection defenses. The  has considerable computation power and is aware of the defense strategies so he can adaptively modifies the attack to counter the defense.
- Claimed to bypass 12 current defenses with attack success-rate of 90%
- Prompting defenses:
    - Spotlighting, Prompt Sandwiching; adding special system instructions to prevent leakage (special delimiter tokens or trusted prompt after the untrusted input) -> search based attacks and human red-teaming -> 1% ASR to 95%
    - RPO; gradient-based prompt optimizations to find a harmless prompt -> attack with same technique using adaptive RL or gradient-based -> ASR 98% - 96%
- Training against existing attacks:
    - Generate adversarial inputs and train the model to generalize on existing attacks -> RL-based attacker -> 2% ASR to 96%
- Filtering defense
    - Standalone detector in front or after the model to filter harmful input/output -> search based attack -> 90% ASR
- Secret knowledge defense
    - Checks a known secret signal in evaluation process -> RL-based attack -> search-based attack -> ASR 76%


## Unclear Points
- Couldn't understand the secret knowledge defense; how do they keep a secret "canary" and evaluate it in run-time?
