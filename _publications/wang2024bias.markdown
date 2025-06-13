---
layout: publication
title: 'Bias Amplification: Large Language Models As Increasingly Biased Media'
authors: Ze Wang, Zekun Wu, Jeremy Zhang, Xin Guan, Navya Jain, Skylar Lu, Saloni Gupta, Adriano Koshiyama
conference: "Arxiv"
year: 2024
bibkey: wang2024bias
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15234'}
tags: ['RAG', 'GPT', 'Tools', 'Training Techniques', 'Model Architecture', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Model collapse, a phenomenon characterized by performance degradation due to iterative training on synthetic data, has been widely studied. However, its implications for bias amplification, the progressive intensification of pre-existing societal biases in Large Language Models (LLMs), remain significantly underexplored, despite the growing influence of LLMs in shaping online discourse. In this paper, we introduce a open, generational, and long-context benchmark specifically designed to measure political bias amplification in LLMs, leveraging sentence continuation tasks derived from a comprehensive dataset of U.S. political news. Our empirical study using GPT-2 reveals consistent and substantial political bias intensification (e.g., right-leaning amplification) over iterative synthetic training cycles. We evaluate three mitigation strategies, Overfitting, Preservation, and Accumulation, and demonstrate that bias amplification persists independently of model collapse, even when the latter is effectively controlled. Furthermore, we propose a mechanistic analysis approach that identifies neurons correlated with specific phenomena during inference through regression and statistical tests. This analysis uncovers largely distinct neuron populations driving bias amplification and model collapse, underscoring fundamentally different underlying mechanisms. Finally, we supplement our empirical findings with theoretical intuition that explains the separate origins of these phenomena, guiding targeted strategies for bias mitigation.
