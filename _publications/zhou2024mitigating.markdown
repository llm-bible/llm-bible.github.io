---
layout: publication
title: 'Mitigating Modality Prior-induced Hallucinations In Multimodal Large Language Models Via Deciphering Attention Causality'
authors: Guanyu Zhou, Yibo Yan, Xin Zou, Kun Wang, Aiwei Liu, Xuming Hu
conference: "Arxiv"
year: 2024
bibkey: zhou2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04780"}
  - {name: "Code", url: "https://github.com/The-Martyr/CausalMM"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Multimodal Large Language Models (MLLMs) have emerged as a central focus in
both industry and academia, but often suffer from biases introduced by visual
and language priors, which can lead to multimodal hallucination. These biases
arise from the visual encoder and the Large Language Model (LLM) backbone,
affecting the attention mechanism responsible for aligning multimodal inputs.
Existing decoding-based mitigation methods focus on statistical correlations
and overlook the causal relationships between attention mechanisms and model
output, limiting their effectiveness in addressing these biases. To tackle this
issue, we propose a causal inference framework termed CausalMM that applies
structural causal modeling to MLLMs, treating modality priors as a confounder
between attention mechanisms and output. Specifically, by employing backdoor
adjustment and counterfactual reasoning at both the visual and language
attention levels, our method mitigates the negative effects of modality priors
and enhances the alignment of MLLM's inputs and outputs, with a maximum score
improvement of 65.3% on 6 VLind-Bench indicators and 164 points on MME
Benchmark compared to conventional methods. Extensive experiments validate the
effectiveness of our approach while being a plug-and-play solution. Our code is
available at: https://github.com/The-Martyr/CausalMM
