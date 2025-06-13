---
layout: publication
title: 'The Order Effect: Investigating Prompt Sensitivity To Input Order In Llms'
authors: Bryan Guan, Tanya Roosta, Peyman Passban, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2025
bibkey: guan2025order
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04134"}
tags: ['Few-Shot', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Prompting', 'Applications', 'In-Context Learning']
---
As large language models (LLMs) become integral to diverse applications, ensuring their reliability under varying input conditions is crucial. One key issue affecting this reliability is order sensitivity, wherein slight variations in the input arrangement can lead to inconsistent or biased outputs. Although recent advances have reduced this sensitivity, the problem remains unresolved. This paper investigates the extent of order sensitivity in LLMs whose internal components are hidden from users (such as closed-source models or those accessed via API calls). We conduct experiments across multiple tasks, including paraphrasing, relevance judgment, and multiple-choice questions. Our results show that input order significantly affects performance across tasks, with shuffled inputs leading to measurable declines in output accuracy. Few-shot prompting demonstrates mixed effectiveness and offers partial mitigation; however, fails to fully resolve the problem. These findings highlight persistent risks, particularly in high-stakes applications, and point to the need for more robust LLMs or improved input-handling techniques in future development.
