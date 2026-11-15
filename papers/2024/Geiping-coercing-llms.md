# Coercing LLMs to do and reveal (almost) anything

*Skimmed*

## Quick Notes
- They forced LLMs to behave in an unintended way and show cased different types of attacks possible on LLMs including; extraction attack (system prompt repeaters), denial of service, control attacks (fake refund)
- Assumed attacker white-box access to open-source models to produce the attack prompts easier, however the black-box attacker transfer same attack with higher computational cost 
- Used various strategies to produce harmful prompts, including Reprogramming (to imply new rulesets as part of codes), language-switching, role hacking (using especial formatting tokens and opened and unclosed parenthesis, brackets or quotes), calls to actions and appeals to authority
- Used glitch tokens to produce harmful prompts but also stated that they're preventable by auditing the tokenizer and they aren’t necessary for attacks to succeed

## Unclear points
- I still don't understand how "calls to action" and "appeal to authority" strategies work