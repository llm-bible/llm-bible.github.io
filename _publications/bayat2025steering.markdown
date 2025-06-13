---
layout: publication
title: 'Steering Large Language Model Activations In Sparse Spaces'
authors: Reza Bayat, Ali Rahimi-kalahroudi, Mohammad Pezeshki, Sarath Chandar, Pascal Vincent
conference: "Arxiv"
year: 2025
bibkey: bayat2025steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00177"}
tags: ['Interpretability and Explainability', 'RAG', 'Prompting', 'Reinforcement Learning']
---
A key challenge in AI alignment is guiding large language models (LLMs) to
follow desired behaviors at test time. Activation steering, which modifies
internal model activations during inference, offers a potential solution.
However, prior work in dense activation spaces struggles with superposition,
wherein multiple features become entangled, limiting interpretability and
precise control. In contrast, sparse representations provide an untapped
opportunity for more interpretable behavior modulation. In this work, we
introduce sparse activation steering (SAS), a method that leverages sparse
autoencoders (SAEs) to steer LLM behavior in sparse spaces. By isolating
behavior-specific features through a contrastive prompt-pairing approach, we
define a set of features that can selectively reinforce or suppress behaviors.
Experiments on Gemma 2 LLMs show that SAS vectors enable nuanced behavioral
modulation and finer-grained control. Furthermore, scaling SAEs improves
monosemanticity of SAS vectors, suggesting more reliable and interpretable
interventions.
