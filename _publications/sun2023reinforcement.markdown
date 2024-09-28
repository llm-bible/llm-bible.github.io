---
layout: publication
title: Reinforcement Learning in the Era of LLMs What is Essential What is needed An RL Perspective on RLHF Prompting and Beyond
authors: Sun Hao
conference: "Arxiv"
year: 2023
bibkey: sun2023reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06147"}
tags: ['ARXIV', 'Agentic', 'Attention Mechanism', 'Chatgpt', 'Fine Tuning', 'GPT', 'LLM', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Recent advancements in Large Language Models (LLMs) have garnered wide attention and led to successful products such as ChatGPT and GPT-4. Their proficiency in adhering to instructions and delivering harmless helpful and honest (3H) responses can largely be attributed to the technique of Reinforcement Learning from Human Feedback (RLHF). In this paper we aim to link the research in conventional RL to RL techniques used in LLM research. Demystify this technique by discussing why when and how RL excels. Furthermore we explore potential future avenues that could either benefit from or contribute to RLHF research. Highlighted Takeaways 1. RLHF is Online Inverse RL with Offline Demonstration Data. 2. RLHF SFT because Imitation Learning (and Inverse RL) Behavior Cloning (BC) by alleviating the problem of compounding error. 3. The RM step in RLHF generates a proxy of the expensive human feedback such an insight can be generalized to other LLM tasks such as prompting evaluation and optimization where feedback is also expensive. 4. The policy learning in RLHF is more challenging than conventional problems studied in IRL due to their high action dimensionality and feedback sparsity. 5. The main superiority of PPO over off-policy value-based methods is its stability gained from (almost) on-policy data and conservative policy updates.
