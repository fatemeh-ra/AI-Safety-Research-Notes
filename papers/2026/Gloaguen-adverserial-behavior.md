# Watch your steps: Dormant Adversarial Behaviors that Activate upon LLM Finetuning

*Skimmed*

## Quick Notes
- Fine-tuning triggers an adversarial behavior in a benign looking model. This attack is agnostic to the fine-tuning dataset, algorithm, number of epochs, etc.
- They fine-tune the base model with a meta-learning algorithm to plant the target behavior while performing benignly; exhibiting no signs of that behavior without fine-tuning and passing all safety benchmarks
- The attack target behaviors are: un-solicited advertising, jailbreakability, and over-refusal
- It's similar to quantization attacks where compressing the model triggers the adversarial behavior, and interestingly the 4-bit quantization probe can also detect this attack, it's like a weaker form of quantization attacks
