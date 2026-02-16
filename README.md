# MoRE: Mixture-of-Recognized-Experts

MoRE (Mixture-of-Recognized-Experts) is a training-free compression framework that transforms static redundancy in pretrained Transformers into input-dependent sparse computation.

Unlike conventional pruning methods that permanently remove parameters based on global importance estimates, MoRE enables an **MoE-style** conditional computation at inference time without modifying model weights. It leverages the hybrid latent structure of pretrained MLP layers — a shared backbone consistently activated across inputs and input-dependent residual components — to dynamically activate different parameter subsets for different inputs.

🚧 This repository is currently a placeholder and will be updated with code, experiments, and documentation.
