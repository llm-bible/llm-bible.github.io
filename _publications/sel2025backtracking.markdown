---
layout: publication
title: 'Backtracking For Safety'
authors: Bilgehan Sel, Dingcheng Li, Phillip Wallis, Vaishakh Keshava, Ming Jin, Siddhartha Reddy Jonnalagadda
conference: "Arxiv"
year: 2025
bibkey: sel2025backtracking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08919'}
tags: ['Agentic', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities across
various tasks, but ensuring their safety and alignment with human values
remains crucial. Current safety alignment methods, such as supervised
fine-tuning and reinforcement learning-based approaches, can exhibit
vulnerabilities to adversarial attacks and often result in shallow safety
alignment, primarily focusing on preventing harmful content in the initial
tokens of the generated output. While methods like resetting can help recover
from unsafe generations by discarding previous tokens and restarting the
generation process, they are not well-suited for addressing nuanced safety
violations like toxicity that may arise within otherwise benign and lengthy
generations. In this paper, we propose a novel backtracking method designed to
address these limitations. Our method allows the model to revert to a safer
generation state, not necessarily at the beginning, when safety violations
occur during generation. This approach enables targeted correction of
problematic segments without discarding the entire generated text, thereby
preserving efficiency. We demonstrate that our method dramatically reduces
toxicity appearing through the generation process with minimal impact to
efficiency.
