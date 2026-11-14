# Privacy Backdoors: Enhancing Membership Inference through Poisoning Pre-trained Models

*Skimmed*

## Quick Notes
- Developed a privacy backdoor attack targeting the pre-trained models, where the adversary adjust the foundation model weights to leak information after fine-tuning happens
- With an specific attack set, they increase the data points loss so that the loss change after the fine-tuning is detectable
- Specifically for LLMs they increase the data points loss, forcing the model to memorize the points before fine-tuning
- The difference in method is linked to different memorization mechanisms in vision and language models

## Unclear points
- Have to read more about the quantization and watermarking inference strategies
