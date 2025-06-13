---
layout: publication
title: 'NLSR: Neuron-level Safety Realignment Of Large Language Models Against Harmful Fine-tuning'
authors: Xin Yi, Shunfan Zheng, Linlin Wang, Gerard De Melo, Xiaoling Wang, Liang He
conference: "Arxiv"
year: 2024
bibkey: yi2024neuron
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12497"}
  - {name: "Code", url: "https://github.com/xinykou/NLSR"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The emergence of finetuning-as-a-service has revealed a new vulnerability in
large language models (LLMs). A mere handful of malicious data uploaded by
users can subtly manipulate the finetuning process, resulting in an
alignment-broken model. Existing methods to counteract fine-tuning attacks
typically require substantial computational resources. Even with
parameter-efficient techniques like LoRA, gradient updates remain essential. To
address these challenges, we propose \textbf\{N\}euron-\textbf\{L\}evel
\textbf\{S\}afety \textbf\{R\}ealignment (\textbf\{NLSR\}), a training-free framework
that restores the safety of LLMs based on the similarity difference of
safety-critical neurons before and after fine-tuning. The core of our framework
is first to construct a safety reference model from an initially aligned model
to amplify safety-related features in neurons. We then utilize this reference
model to identify safety-critical neurons, which we prepare as patches.
Finally, we selectively restore only those neurons that exhibit significant
similarity differences by transplanting these prepared patches, thereby
minimally altering the fine-tuned model. Extensive experiments demonstrate
significant safety enhancements in fine-tuned models across multiple downstream
tasks, while greatly maintaining task-level accuracy. Our findings suggest
regions of some safety-critical neurons show noticeable differences after
fine-tuning, which can be effectively corrected by transplanting neurons from
the reference model without requiring additional training. The code will be
available at \url\{https://github.com/xinykou/NLSR\}
