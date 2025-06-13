---
layout: publication
title: 'Lookahead Tuning: Safer Language Models Via Partial Answer Previews'
authors: Kangwei Liu, Mengru Wang, Yujie Luo, Lin Yuan, Mengshu Sun, Ningyu Zhang, Lei Liang, Zhiqiang Zhang, Jun Zhou, Huajun Chen
conference: "Arxiv"
year: 2025
bibkey: liu2025lookahead
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19041"}
  - {name: "Code", url: "https://github.com/zjunlp/LookAheadTuning"}
tags: ['Responsible AI', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Fine-tuning enables large language models (LLMs) to adapt to specific
domains, but often undermines their previously established safety alignment. To
mitigate the degradation of model safety during fine-tuning, we introduce
LookAhead Tuning, which comprises two simple, low-resource, and effective
data-driven methods that modify training data by previewing partial answer
prefixes. Both methods aim to preserve the model's inherent safety mechanisms
by minimizing perturbations to initial token distributions. Comprehensive
experiments demonstrate that LookAhead Tuning effectively maintains model
safety without sacrificing robust performance on downstream tasks. Our findings
position LookAhead Tuning as a reliable and efficient solution for the safe and
effective adaptation of LLMs. Code is released at
https://github.com/zjunlp/LookAheadTuning.
