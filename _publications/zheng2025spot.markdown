---
layout: publication
title: 'Spot Risks Before Speaking! Unraveling Safety Attention Heads In Large Vision-language Models'
authors: Ziwei Zheng, Junyao Zhao, Le Yang, Lijun He, Fan Li
conference: "Arxiv"
year: 2025
bibkey: zheng2025spot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02029"}
  - {name: "Code", url: "https://github.com/Ziwei-Zheng/SAHs"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Attention Mechanism']
---
With the integration of an additional modality, large vision-language models
(LVLMs) exhibit greater vulnerability to safety risks (e.g., jailbreaking)
compared to their language-only predecessors. Although recent studies have
devoted considerable effort to the post-hoc alignment of LVLMs, the inner
safety mechanisms remain largely unexplored. In this paper, we discover that
internal activations of LVLMs during the first token generation can effectively
identify malicious prompts across different attacks. This inherent safety
perception is governed by sparse attention heads, which we term ``safety
heads." Further analysis reveals that these heads act as specialized shields
against malicious prompts; ablating them leads to higher attack success rates,
while the model's utility remains unaffected. By locating these safety heads
and concatenating their activations, we construct a straightforward but
powerful malicious prompt detector that integrates seamlessly into the
generation process with minimal extra inference overhead. Despite its simple
structure of a logistic regression model, the detector surprisingly exhibits
strong zero-shot generalization capabilities. Experiments across various
prompt-based attacks confirm the effectiveness of leveraging safety heads to
protect LVLMs. Code is available at \url\{https://github.com/Ziwei-Zheng/SAHs\}.
