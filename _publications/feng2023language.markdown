---
layout: publication
title: "Language Models Can Be Logical Solvers"
authors: Feng Jiazhan, Xu Ruochen, Hao Junheng, Sharma Hiteshi, Shen Yelong, Zhao Dongyan, Chen Weizhu
conference: "Arxiv"
year: 2023
bibkey: feng2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06158"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting']
---
Logical reasoning is a fundamental aspect of human intelligence and a key component of tasks like problem-solving and decision-making. Recent advancements have enabled Large Language Models (LLMs) to potentially exhibit reasoning capabilities but complex logical reasoning remains a challenge. The state-of-the-art solver-augmented language models use LLMs to parse natural language logical questions into symbolic representations first and then adopt external logical solvers to take in the symbolic representations and output the answers. Despite their impressive performance any parsing errors will inevitably result in the failure of the execution of the external logical solver and no answer to the logical questions. In this paper we introduce LoGiPT a novel language model that directly emulates the reasoning processes of logical solvers and bypasses the parsing errors by learning to strict adherence to solver syntax and grammar. LoGiPT is fine-tuned on a newly constructed instruction-tuning dataset derived from revealing and refining the invisible reasoning process of deductive solvers. Experimental results on two public deductive reasoning datasets demonstrate that LoGiPT outperforms state-of-the-art solver-augmented LMs and few-shot prompting methods on competitive LLMs like ChatGPT or GPT-4.
