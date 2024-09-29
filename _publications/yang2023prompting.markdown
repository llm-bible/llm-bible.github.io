---
layout: publication
title: Alignedcot: Prompting Large Language Models Via Native-speaking Demonstrations
authors: Yang Zhicheng, Huang Yinya, Xiong Jing, Feng Liang, Liang Xiaodan, Wang Yiwei, Tang Jing
conference: "Arxiv"
year: 2023
bibkey: yang2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13538"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'Training Techniques']
---
Large Language Models prompting such as using in-context demonstrations is a mainstream technique for invoking LLMs to perform high-performance and solid complex reasoning (e.g. mathematical reasoning commonsense reasoning) and has the potential for further human-machine collaborative scientific findings. However current LLMs are delicate and elusive in prompt words and styles. And there is an unseen gap between LLM understanding and human-written prompts. This paper introduces AlignedCoT an LLM-acquainted prompting technique that includes proficient native-speaking in in-context learning for the LLMs. Specifically it achieves consistent and correct step-wise prompts in zero-shot scenarios by progressively probing refining and formatting the LLM chain of thoughts so that free from handcrafted few-shot demonstrations while maintaining the prompt quality. We conduct experiments on mathematical reasoning and commonsense reasoning. We find that LLMs with AlignedCoT perform significantly superior to them with human-crafted demonstrations. We further apply AlignedCoT for rewriting the GSM8k training set resulting in a GSM8k-Align dataset. We observe its benefits for retrieval augmented generation.
