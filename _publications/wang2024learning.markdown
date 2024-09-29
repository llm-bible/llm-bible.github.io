---
layout: publication
title: Learning To Ask\: When Llms Meet Unclear Instruction
authors: Wang Wenxuan, Shi Juluan, Wang Chaozheng, Lee Cheryl, Yuan Youliang, Huang Jen-tse, Lyu Michael R.
conference: "Arxiv"
year: 2024
bibkey: wang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00557"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'TACL', 'Tools', 'Training Techniques']
---
Equipped with the capability to call functions modern large language models (LLMs) can leverage external tools for addressing a range of tasks unattainable through language skills alone. However the effective execution of these tools relies heavily not just on the advanced capabilities of LLMs but also on precise user instructions which often cannot be ensured in the real world. To evaluate the performance of LLMs tool-use under imperfect instructions we meticulously examine the real-world instructions queried from users analyze the error patterns and build a challenging tool-use benchmark called Noisy ToolBench (NoisyToolBench). We find that due to the next-token prediction training objective LLMs tend to arbitrarily generate the missed argument which may lead to hallucinations and risks. To address this issue we propose a novel framework Ask-when-Needed (AwN) which prompts LLMs to ask questions to users whenever they encounter obstacles due to unclear instructions. Moreover to reduce the manual labor involved in user-LLM interaction and assess LLMs performance in tool utilization from both accuracy and efficiency perspectives we design an automated evaluation tool named ToolEvaluator. Our experiments demonstrate that the AwN significantly outperforms existing frameworks for tool learning in the NoisyToolBench. We will release all related code and datasets to support future research.
