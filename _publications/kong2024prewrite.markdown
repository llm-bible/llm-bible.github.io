---
layout: publication
title: PRewrite Prompt Rewriting with Reinforcement Learning
authors: Kong Weize, Hombaiah Spurthi Amba, Zhang Mingyang, Mei Qiaozhu, Bendersky Michael
conference: "Arxiv"
year: 2024
bibkey: kong2024prewrite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08189"}
tags: ['Agentic', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Prompt engineering is critical for the development of LLM-based applications. However it is usually done manually in a trial and error fashion that can be time consuming ineffective and sub-optimal. Even for the prompts which seemingly work well there is always a lingering question can the prompts be made better with further modifications To address these problems we investigate automated prompt engineering in this paper. Specifically we propose PRewrite an automated method to rewrite an under-optimized prompt to a more effective prompt. We instantiate the prompt rewriter using a LLM. The rewriter LLM is trained using reinforcement learning to optimize the performance on a given downstream task. We conduct experiments on diverse benchmark datasets which demonstrates the effectiveness of PRewrite.
