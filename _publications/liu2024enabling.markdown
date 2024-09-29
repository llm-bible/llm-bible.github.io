---
layout: publication
title: Enabling Weak LLMs to Judge Response Reliability via Meta Ranking
authors: Liu Zijun, Kou Boqun, Li Peng, Yan Ming, Zhang Ji, Huang Fei, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: liu2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12146"}
tags: ['Applications', 'Efficiency And Optimization', 'Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Despite the strong performance of large language models (LLMs) across a wide range of tasks they still have reliability issues. Previous studies indicate that strong LLMs like GPT-4-turbo excel in evaluating the reliability of responses from LLMs but face efficiency and local deployment issues. Thus to enable weak LLMs to effectively assess the reliability of LLM responses we propose a novel cross-query-comparison-based method called (MR). Unlike previous few-shot methods that solely based on in-context learning capabilities in LLMs MR assesses reliability by pairwisely ranking the target query-response pair with multiple reference query-response pairs. We found that MR is highly effective in error detection for LLM responses where weak LLMs such as Phi-2 could surpass strong baselines like GPT-3.5-turbo requiring only five reference samples and significantly improving efficiency. We further demonstrate that MR can enhance strong LLMs performance in two practical applications model cascading and instruction tuning. In model cascading we combine open- and closed-source LLMs to achieve performance comparable to GPT-4-turbo with lower costs. In instruction tuning we use MR for iterative training data filtering significantly reducing data processing time and enabling LLaMA-7B and Phi-2 to surpass Alpaca-13B with fewer training tokens. These results underscore the high potential of MR in both efficiency and effectiveness.
