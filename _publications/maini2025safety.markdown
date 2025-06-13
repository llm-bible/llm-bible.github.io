---
layout: publication
title: 'Safety Pretraining: Toward The Next Generation Of Safe AI'
authors: Pratyush Maini, Sachin Goyal, Dylan Sam, Alex Robey, Yash Savani, Yiding Jiang, Andy Zou, Zacharcy C. Lipton, J. Zico Kolter
conference: "Arxiv"
year: 2025
bibkey: maini2025safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16980"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
As large language models (LLMs) are increasingly deployed in high-stakes
settings, the risk of generating harmful or toxic content remains a central
challenge. Post-hoc alignment methods are brittle: once unsafe patterns are
learned during pretraining, they are hard to remove. We present a data-centric
pretraining framework that builds safety into the model from the start. Our
contributions include: (i) a safety classifier trained on 10,000 GPT-4 labeled
examples, used to filter 600B tokens; (ii) the largest synthetic safety dataset
to date (100B tokens) generated via recontextualization of harmful web data;
(iii) RefuseWeb and Moral Education datasets that convert harmful prompts into
refusal dialogues and web-style educational material; (iv) Harmfulness-Tag
annotations injected during pretraining to flag unsafe content and steer away
inference from harmful generations; and (v) safety evaluations measuring base
model behavior before instruction tuning. Our safety-pretrained models reduce
attack success rates from 38.8% to 8.4% with no performance degradation on
standard LLM safety benchmarks.
