---
layout: publication
title: LUQ&#58; Long-text Uncertainty Quantification For Llms
authors: Zhang Caiqi, Liu Fangyu, Basaldella Marco, Collier Nigel
conference: "Arxiv"
year: 2024
bibkey: zhang2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20279"}
tags: ['Applications', 'Language Modeling', 'Merging', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated remarkable capability in a variety of NLP tasks. However LLMs are also prone to generate nonfactual content. Uncertainty Quantification (UQ) is pivotal in enhancing our understanding of a models confidence on its generation thereby aiding in the mitigation of nonfactual outputs. Existing research on UQ predominantly targets short text generation typically yielding brief word-limited responses. However real-world applications frequently necessitate much longer responses. Our study first highlights the limitations of current UQ methods in handling long text generation. We then introduce (textscLuq) and its two variations a series of novel sampling-based UQ approaches specifically designed for long text. Our findings reveal that (textscLuq) outperforms existing baseline methods in correlating with the models factuality scores (negative coefficient of -0.85 observed for Gemini Pro). To further improve the factuality of LLM responses we propose (textsc)Luq-Ensemble a method that ensembles responses from multiple models and selects the response with the lowest uncertainty. The ensembling method greatly improves the response factuality upon the best standalone LLM.
