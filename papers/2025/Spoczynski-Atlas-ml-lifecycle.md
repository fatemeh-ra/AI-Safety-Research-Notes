# Atlas: A Framework for ML Lifecycle Provenance & Transparency

*Skimmed*


## Quick Notes
- An end-to-end attestable ML pipeline framework with verifiable integrity, proveanance and lineage meta-data combined with hardware-backed security (runing in TEE)
- In ML, dataset and code is coupled with the result so they should be attested
- Learning is not a linear developement process so they provided an auditing schema based on Merkle Tree hash to support non-linear scenarios. Each step is linked to the previous one to produce an attestable history, just like blockchain.
- ML provider can NOT poison data samples during training or use a different dataset and model with a mismatched signature
- They can not validate the base model trustworthiness, its part of the framework assumptions
