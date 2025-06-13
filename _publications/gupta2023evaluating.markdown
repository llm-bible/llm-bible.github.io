---
layout: publication
title: 'Evaluating Concurrent Robustness Of Language Models Across Diverse Challenge Sets'
authors: Vatsal Gupta, Pranshu Pandya, Tushar Kataria, Vivek Gupta, Dan Roth
conference: "Arxiv"
year: 2023
bibkey: gupta2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08662"}
tags: ['Fine-Tuning', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Language models, characterized by their black-box nature, often hallucinate
and display sensitivity to input perturbations, causing concerns about trust.
To enhance trust, it is imperative to gain a comprehensive understanding of the
model's failure modes and develop effective strategies to improve their
performance. In this study, we introduce a methodology designed to examine how
input perturbations affect language models across various scales, including
pre-trained models and large language models (LLMs). Utilizing fine-tuning, we
enhance the model's robustness to input perturbations. Additionally, we
investigate whether exposure to one perturbation enhances or diminishes the
model's performance with respect to other perturbations. To address robustness
against multiple perturbations, we present three distinct fine-tuning
strategies. Furthermore, we broaden the scope of our methodology to encompass
large language models (LLMs) by leveraging a chain of thought (CoT) prompting
approach augmented with exemplars. We employ the Tabular-NLI task to showcase
how our proposed strategies adeptly train a robust model, enabling it to
address diverse perturbations while maintaining accuracy on the original
dataset. https://msin-infotabs.github.io/
