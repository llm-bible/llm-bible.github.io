---
layout: publication
title: Defending Large Language Models Against Jailbreak Attacks Via Layer45;specific Editing
authors: Zhao Wei, Li Zhe, Li Yige, Zhang Ye, Sun Jun
conference: "Arxiv"
year: 2024
bibkey: zhao2024defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18166"}
  - {name: "Code", url: "https://github.com/ledllm/ledllm&#125;"}
tags: ['Agentic', 'Applications', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Large language models (LLMs) are increasingly being adopted in a wide range of real45;world applications. Despite their impressive performance recent studies have shown that LLMs are vulnerable to deliberately crafted adversarial prompts even when aligned via Reinforcement Learning from Human Feedback or supervised fine45;tuning. While existing defense methods focus on either detecting harmful prompts or reducing the likelihood of harmful responses through various means defending LLMs against jailbreak attacks based on the inner mechanisms of LLMs remains largely unexplored. In this work we investigate how LLMs response to harmful prompts and propose a novel defense method termed textbf123;L125;ayer45;specific textbf123;Ed125;iting (LED) to enhance the resilience of LLMs against jailbreak attacks. Through LED we reveal that several critical textit123;safety layers125; exist among the early layers of LLMs. We then show that realigning these safety layers (and some selected additional layers) with the decoded safe response from selected target layers can significantly improve the alignment of LLMs against jailbreak attacks. Extensive experiments across various LLMs (e.g. Llama2 Mistral) show the effectiveness of LED which effectively defends against jailbreak attacks while maintaining performance on benign prompts. Our code is available at url123;https://github.com/ledllm/ledllm&#125;.
