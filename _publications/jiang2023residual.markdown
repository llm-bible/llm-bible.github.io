---
layout: publication
title: 'Resprompt: Residual Connection Prompting Advances Multi-step Reasoning In Large Language Models'
authors: Song Jiang, Zahra Shakeri, Aaron Chan, Maziar Sanjabi, Hamed Firooz, Yinglong Xia, Bugra Akyildiz, Yizhou Sun, Jinchao Li, Qifan Wang, Asli Celikyilmaz
conference: "Arxiv"
year: 2023
bibkey: jiang2023residual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.04743'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting']
---
Chain-of-thought (CoT) prompting, which offers step-by-step problem-solving
rationales, has impressively unlocked the reasoning potential of large language
models (LLMs). Yet, the standard CoT is less effective in problems demanding
multiple reasoning steps. This limitation arises from the complex reasoning
process in multi-step problems: later stages often depend on the results of
several steps earlier, not just the results of the immediately preceding step.
Such complexities suggest the reasoning process is naturally represented as a
graph. The almost linear and straightforward structure of CoT prompting,
however, struggles to capture this complex reasoning graph. To address this
challenge, we propose Residual Connection Prompting (RESPROMPT), a new
prompting strategy that advances multi-step reasoning in LLMs. Our key idea is
to reconstruct the reasoning graph within prompts. We achieve this by
integrating necessary connections-links present in the reasoning graph but
missing in the linear CoT flow-into the prompts. Termed "residual connections",
these links are pivotal in morphing the linear CoT structure into a graph
representation, effectively capturing the complex reasoning graphs inherent in
multi-step problems. We evaluate RESPROMPT on six benchmarks across three
diverse domains: math, sequential, and commonsense reasoning. For the
open-sourced LLaMA family of models, RESPROMPT yields a significant average
reasoning accuracy improvement of 12.5% on LLaMA-65B and 6.8% on LLaMA2-70B.
Breakdown analysis further highlights RESPROMPT particularly excels in complex
multi-step reasoning: for questions demanding at least five reasoning steps,
RESPROMPT outperforms the best CoT based benchmarks by a remarkable average
improvement of 21.1% on LLaMA-65B and 14.3% on LLaMA2-70B. Through extensive
ablation studies and analyses, we pinpoint how to most effectively build
residual connections.
