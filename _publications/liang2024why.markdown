---
layout: publication
title: 'Why Are My Prompts Leaked? Unraveling Prompt Extraction Threats In Customized Large Language Models'
authors: Liang Zi, Hu Haibo, Ye Qingqing, Xiao Yaxin, Li Haoyang
conference: "Arxiv"
year: 2024
bibkey: liang2024why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02416"}
  - {name: "Code", url: "https://github.com/liangzid/PromptExtractionEval"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Scaling Laws', 'Security', 'Training Techniques']
---
"The drastic increase of large language models' (LLMs) parameters has led to a new research direction of fine-tuning-free downstream customization by prompts, i.e., task descriptions. While these prompt-based services (e.g. OpenAI's GPTs) play an important role in many businesses, there has emerged growing concerns about the prompt leakage, which undermines the intellectual properties of these services and causes downstream attacks. In this paper, we analyze the underlying mechanism of prompt leakage, which we refer to as prompt memorization, and develop corresponding defending strategies. By exploring the scaling laws in prompt extraction, we analyze key attributes that influence prompt extraction, including model sizes, prompt lengths, as well as the types of prompts. Then we propose two hypotheses that explain how LLMs expose their prompts. The first is attributed to the perplexity, i.e. the familiarity of LLMs to texts, whereas the second is based on the straightforward token translation path in attention matrices. To defend against such threats, we investigate whether alignments can undermine the extraction of prompts. We find that current LLMs, even those with safety alignments like GPT-4, are highly vulnerable to prompt extraction attacks, even under the most straightforward user attacks. Therefore, we put forward several defense strategies with the inspiration of our findings, which achieve 83.8\&#37; and 71.0\&#37; drop in the prompt extraction rate for Llama2-7B and GPT-3.5, respectively. Source code is avaliable at \url\{https://github.com/liangzid/PromptExtractionEval\}."
