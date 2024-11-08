---
layout: publication
title: 'Machine Unlearning In Large Language Models'
authors: Chen Kongyang, Wang Zixin, Mi Bing, Liu Waixi, Wang Shaowei, Ren Xiaojun, Shen Jiaxing
conference: "Arxiv"
year: 2024
bibkey: chen2024machine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16841"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'Security', 'Tools']
---
Recently, large language models (LLMs) have emerged as a notable field,
attracting significant attention for its ability to automatically generate
intelligent contents for various application domains. However, LLMs still
suffer from significant security and privacy issues. For example, LLMs might
expose user privacy from hacking attacks or targeted prompts. To address this
problem, this paper introduces a novel machine unlearning framework into LLMs.
Our objectives are to make LLMs not produce harmful, hallucinatory, or
privacy-compromising responses, while retaining their standard output
capabilities. To accomplish this, we use an evaluative model to pinpoint
dialogues needing unlearning. We also establish a distance loss to function as
the model's negative loss, diverting it from previous undesirable outputs.
Furthermore, we determine the expected output's cluster mean to formulate a
positive loss, directing the model's outputs toward preferable outcomes without
compromising its reasoning abilities and performance. Experimental results show
that our approach effectively meets unlearning objectives without substantially
compromising model performance.
