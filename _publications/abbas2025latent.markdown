---
layout: publication
title: 'Latent Adversarial Training Improves The Representation Of Refusal'
authors: Alexandra Abbas, Nora Petrova, Helios Ael Lyons, Natalia Perez-campanero
conference: "Arxiv"
year: 2025
bibkey: abbas2025latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18872"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Recent work has shown that language models' refusal behavior is primarily
encoded in a single direction in their latent space, making it vulnerable to
targeted attacks. Although Latent Adversarial Training (LAT) attempts to
improve robustness by introducing noise during training, a key question
remains: How does this noise-based training affect the underlying
representation of refusal behavior? Understanding this encoding is crucial for
evaluating LAT's effectiveness and limitations, just as the discovery of linear
refusal directions revealed vulnerabilities in traditional supervised safety
fine-tuning (SSFT).
  Through the analysis of Llama 2 7B, we examine how LAT reorganizes the
refusal behavior in the model's latent space compared to SSFT and embedding
space adversarial training (AT). By computing activation differences between
harmful and harmless instruction pairs and applying Singular Value
Decomposition (SVD), we find that LAT significantly alters the refusal
representation, concentrating it in the first two SVD components which explain
approximately 75 percent of the activation differences variance - significantly
higher than in reference models. This concentrated representation leads to more
effective and transferable refusal vectors for ablation attacks: LAT models
show improved robustness when attacked with vectors from reference models but
become more vulnerable to self-generated vectors compared to SSFT and AT. Our
findings suggest that LAT's training perturbations enable a more comprehensive
representation of refusal behavior, highlighting both its potential strengths
and vulnerabilities for improving model safety.
