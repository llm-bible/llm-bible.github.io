---
layout: publication
title: Enabling Weak Llms To Judge Response Reliability Via Meta Ranking
authors: Liu Zijun, Kou Boqun, Li Peng, Yan Ming, Zhang Ji, Huang Fei, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: liu2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12146"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Despite the strong performance of large language models (LLMs) across a wide range of tasks they still have reliability issues. Previous studies indicate that strong LLMs like GPT45;445;turbo excel in evaluating the reliability of responses from LLMs but face efficiency and local deployment issues. Thus to enable weak LLMs to effectively assess the reliability of LLM responses we propose a novel cross45;query45;comparison45;based method called textit123;Meta Ranking125; (MR). Unlike previous few45;shot methods that solely based on in45;context learning capabilities in LLMs MR assesses reliability by pairwisely ranking the target query45;response pair with multiple reference query45;response pairs. We found that MR is highly effective in error detection for LLM responses where weak LLMs such as Phi45;2 could surpass strong baselines like GPT45;3.545;turbo requiring only five reference samples and significantly improving efficiency. We further demonstrate that MR can enhance strong LLMs performance in two practical applications model cascading and instruction tuning. In model cascading we combine open45; and closed45;source LLMs to achieve performance comparable to GPT45;445;turbo with lower costs. In instruction tuning we use MR for iterative training data filtering significantly reducing data processing time and enabling LLaMA45;7B and Phi45;2 to surpass Alpaca45;13B with fewer training tokens. These results underscore the high potential of MR in both efficiency and effectiveness.
