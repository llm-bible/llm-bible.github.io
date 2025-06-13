---
layout: publication
title: 'Deepseek On A Trip: Inducing Targeted Visual Hallucinations Via Representation Vulnerabilities'
authors: Chashi Mahiul Islam, Samuel Jacob Chacko, Preston Horne, Xiuwen Liu
conference: "Arxiv"
year: 2025
bibkey: islam2025deepseek
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07905"}
tags: ['Responsible AI', 'Security', 'Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Merging', 'Ethics and Bias', 'Prompting']
---
Multimodal Large Language Models (MLLMs) represent the cutting edge of AI
technology, with DeepSeek models emerging as a leading open-source alternative
offering competitive performance to closed-source systems. While these models
demonstrate remarkable capabilities, their vision-language integration
mechanisms introduce specific vulnerabilities. We implement an adapted
embedding manipulation attack on DeepSeek Janus that induces targeted visual
hallucinations through systematic optimization of image embeddings. Through
extensive experimentation across COCO, DALL-E 3, and SVIT datasets, we achieve
hallucination rates of up to 98.0% while maintaining high visual fidelity (SSIM
> 0.88) of the manipulated images on open-ended questions. Our analysis
demonstrates that both 1B and 7B variants of DeepSeek Janus are susceptible to
these attacks, with closed-form evaluation showing consistently higher
hallucination rates compared to open-ended questioning. We introduce a novel
multi-prompt hallucination detection framework using LLaMA-3.1 8B Instruct for
robust evaluation. The implications of these findings are particularly
concerning given DeepSeek's open-source nature and widespread deployment
potential. This research emphasizes the critical need for embedding-level
security measures in MLLM deployment pipelines and contributes to the broader
discussion of responsible AI implementation.
