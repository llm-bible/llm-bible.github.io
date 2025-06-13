---
layout: publication
title: 'The Illusion Of Role Separation: Hidden Shortcuts In LLM Role Learning (and How To Fix Them)'
authors: Zihao Wang, Yibo Jiang, Jiahao Yu, Heqing Huang
conference: "Arxiv"
year: 2025
bibkey: wang2025illusion
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00626'}
tags: ['Prompting', 'Tools']
---
Large language models (LLMs) that integrate multiple input roles (e.g.,
system instructions, user queries, external tool outputs) are increasingly
prevalent in practice. Ensuring that the model accurately distinguishes
messages from each role -- a concept we call *role separation* -- is
crucial for consistent multi-role behavior. Although recent work often targets
state-of-the-art prompt injection defenses, it remains unclear whether such
methods truly teach LLMs to differentiate roles or merely memorize known
triggers. In this paper, we examine *role-separation learning*: the
process of teaching LLMs to robustly distinguish system and user tokens.
Through a *simple, controlled experimental framework*, we find that
fine-tuned models often rely on two proxies for role identification: (1) task
type exploitation, and (2) proximity to begin-of-text. Although data
augmentation can partially mitigate these shortcuts, it generally leads to
iterative patching rather than a deeper fix. To address this, we propose
reinforcing *invariant signals* that mark role boundaries by adjusting
token-wise cues in the model's input encoding. In particular, manipulating
position IDs helps the model learn clearer distinctions and reduces reliance on
superficial proxies. By focusing on this mechanism-centered perspective, our
work illuminates how LLMs can more reliably maintain consistent multi-role
behavior without merely memorizing known prompts or triggers.
