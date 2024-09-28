---
layout: publication
title: Towards Making the Most of ChatGPT for Machine Translation
authors: Peng Keqin, Ding Liang, Zhong Qihuang, Shen Li, Liu Xuebo, Zhang Min, Ouyang Yuanxin, Tao Dacheng
conference: "Arxiv"
year: 2023
bibkey: peng2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.13780"}
tags: ['ARXIV', 'Applications', 'GPT', 'In Context Learning', 'Model Architecture', 'NLP', 'Prompting', 'Reinforcement Learning', 'Tools']
---
ChatGPT shows remarkable capabilities for machine translation (MT). Several prior studies have shown that it achieves comparable results to commercial systems for high-resource languages but lags behind in complex tasks e.g. low-resource and distant-language-pairs translation. However they usually adopt simple prompts which can not fully elicit the capability of ChatGPT. In this paper we aim to further mine ChatGPTs translation ability by revisiting several aspects temperature task information and domain information and correspondingly propose an optimal temperature setting and two (simple but effective) prompts Task-Specific Prompts (TSP) and Domain-Specific Prompts (DSP). We show that 1) The performance of ChatGPT depends largely on temperature and a lower temperature usually can achieve better performance; 2) Emphasizing the task information can further improve ChatGPTs performance particularly in complex MT tasks; 3) Introducing domain information can elicit ChatGPTs generalization ability and improve its performance in the specific domain; 4) ChatGPT tends to generate hallucinations for non-English-centric MT tasks which can be partially addressed by our proposed prompts but still need to be highlighted for the MT/NLP community. We also explore the effects of advanced in-context learning strategies and find a (negative but interesting) observation the powerful chain-of-thought prompt leads to word-by-word translation behavior thus bringing significant translation degradation.
