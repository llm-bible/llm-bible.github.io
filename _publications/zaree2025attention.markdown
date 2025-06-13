---
layout: publication
title: 'Attention Eclipse: Manipulating Attention To Bypass LLM Safety-alignment'
authors: Pedram Zaree, Md Abdullah Al Mamun, Quazi Mishkatul Alam, Yue Dong, Ihsen Alouani, Nael Abu-ghazaleh
conference: "Arxiv"
year: 2025
bibkey: zaree2025attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15334'}
tags: ['Attention Mechanism', 'Security', 'Model Architecture', 'Prompting', 'Responsible AI']
---
Recent research has shown that carefully crafted jailbreak inputs can induce
large language models to produce harmful outputs, despite safety measures such
as alignment. It is important to anticipate the range of potential Jailbreak
attacks to guide effective defenses and accurate assessment of model safety. In
this paper, we present a new approach for generating highly effective Jailbreak
attacks that manipulate the attention of the model to selectively strengthen or
weaken attention among different parts of the prompt. By harnessing attention
loss, we develop more effective jailbreak attacks, that are also transferrable.
The attacks amplify the success rate of existing Jailbreak algorithms including
GCG, AutoDAN, and ReNeLLM, while lowering their generation cost (for example,
the amplified GCG attack achieves 91.2% ASR, vs. 67.9% for the original attack
on Llama2-7B/AdvBench, using less than a third of the generation time).
