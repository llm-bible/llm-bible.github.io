---
layout: publication
title: 'R$^3$ Prompting: Review, Rephrase And Resolve For Chain-of-thought Reasoning In Large Language Models Under Noisy Context'
authors: Tian Qingyuan, Zhu Hanlun, Wang Lei, Li Yang, Lan Yunshi
conference: "Arxiv"
year: 2023
bibkey: tian2023rephrase
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16535"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Security']
---
With the help of Chain-of-Thought (CoT) prompting Large Language Models (LLMs) have achieved remarkable performance on various reasoning tasks. However most of them have been evaluated under noise-free context and the dilemma for LLMs to produce inaccurate results under the noisy context has not been fully investigated. Existing studies utilize trigger sentences to encourage LLMs to concentrate on the relevant information but the trigger has limited effect on final answer prediction. Inspired by interactive CoT method where intermediate reasoning steps are promoted by multiple rounds of interaction between users and LLMs we propose a novel prompting method namely R^3 prompting for CoT reasoning under noisy context. Specifically R^3 prompting interacts with LLMs to perform key sentence extraction variable declaration and answer prediction which corresponds to a thought process of reviewing rephrasing and resolving. The responses generated at the last interaction will perform as hints to guide toward the responses of the next interaction. Our experiments show that R^3 prompting significantly outperforms existing CoT prompting methods on five reasoning tasks under noisy context. With GPT-3.5-turbo we observe 3.737; accuracy improvement on average on the reasoning tasks under noisy context compared to the most competitive prompting baseline. More analyses and ablation studies show the robustness and generalization of R^3 prompting method in solving reasoning tasks in LLMs under noisy context.
