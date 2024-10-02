---
layout: publication
title: 'When Is The Consistent Prediction Likely To Be A Correct Prediction?'
authors: Nguyen Alex, Mekala Dheeraj, Dong Chengyu, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: nguyen2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05778"}
tags: ['Ethics And Bias', 'Prompting']
---
'Self-consistency (Wang et al., 2023) suggests that the most consistent answer obtained through large language models (LLMs) is more likely to be correct. In this paper, we challenge this argument and propose a nuanced correction. Our observations indicate that consistent answers derived through more computation i.e. longer reasoning texts, rather than simply the most consistent answer across all outputs, are more likely to be correct. This is predominantly because we demonstrate that LLMs can autonomously produce chain-of-thought (CoT) style reasoning with no custom prompts merely while generating longer responses, which lead to consistent predictions that are more accurate. In the zero-shot setting, by sampling Mixtral-8x7B model multiple times and considering longer responses, we achieve 86&#37; of its self-consistency performance obtained through zero-shot CoT prompting on the GSM8K and MultiArith datasets. Finally, we demonstrate that the probability of LLMs generating a longer response is quite low, highlighting the need for decoding strategies conditioned on output length.'
