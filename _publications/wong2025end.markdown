---
layout: publication
title: 'An End-to-end Model For Logits Based Large Language Models Watermarking'
authors: Kahim Wong, Jicheng Zhou, Jiantao Zhou, Yain-whar Si
conference: "Arxiv"
year: 2025
bibkey: wong2025end
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02344'}
  - {name: "Code", url: 'https://github.com/KAHIMWONG/E2E_LLM_WM'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
The rise of LLMs has increased concerns over source tracing and copyright protection for AIGC, highlighting the need for advanced detection technologies. Passive detection methods usually face high false positives, while active watermarking techniques using logits or sampling manipulation offer more effective protection. Existing LLM watermarking methods, though effective on unaltered content, suffer significant performance drops when the text is modified and could introduce biases that degrade LLM performance in downstream tasks. These methods fail to achieve an optimal tradeoff between text quality and robustness, particularly due to the lack of end-to-end optimization of the encoder and decoder. In this paper, we introduce a novel end-to-end logits perturbation method for watermarking LLM-generated text. By jointly optimization, our approach achieves a better balance between quality and robustness. To address non-differentiable operations in the end-to-end training pipeline, we introduce an online prompting technique that leverages the on-the-fly LLM as a differentiable surrogate. Our method achieves superior robustness, outperforming distortion-free methods by 37-39% under paraphrasing and 17.2% on average, while maintaining text quality on par with these distortion-free methods in terms of text perplexity and downstream tasks. Our method can be easily generalized to different LLMs. Code is available at https://github.com/KAHIMWONG/E2E_LLM_WM.
