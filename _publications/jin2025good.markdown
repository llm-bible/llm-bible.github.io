---
layout: publication
title: 'Good News For Script Kiddies? Evaluating Large Language Models For Automated Exploit Generation'
authors: David Jin, Qian Fu, Yuekang Li
conference: "Arxiv"
year: 2025
bibkey: jin2025good
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01065'}
tags: ['Security', 'GPT', 'Model Architecture', 'Prompting', 'Ethics and Bias']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
code-related tasks, raising concerns about their potential for automated
exploit generation (AEG). This paper presents the first systematic study on
LLMs' effectiveness in AEG, evaluating both their cooperativeness and technical
proficiency. To mitigate dataset bias, we introduce a benchmark with refactored
versions of five software security labs. Additionally, we design an LLM-based
attacker to systematically prompt LLMs for exploit generation. Our experiments
reveal that GPT-4 and GPT-4o exhibit high cooperativeness, comparable to
uncensored models, while Llama3 is the most resistant. However, no model
successfully generates exploits for refactored labs, though GPT-4o's minimal
errors highlight the potential for LLM-driven AEG advancements.
