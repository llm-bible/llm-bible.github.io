---
layout: publication
title: Exposing Limitations Of Language Model Agents In Sequential45;task Compositions On The Web
authors: Furuta Hiroki, Matsuo Yutaka, Faust Aleksandra, Gur Izzeddin
conference: "Arxiv"
year: 2023
bibkey: furuta2023exposing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18751"}
tags: ['Agent', 'Agentic', 'Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Language model agents (LMA) recently emerged as a promising paradigm on muti45;step decision making tasks often outperforming humans and other reinforcement learning agents. Despite the promise their performance on real45;world applications that often involve combinations of tasks is still underexplored. In this work we introduce a new benchmark called CompWoB 45;45; 50 new compositional web automation tasks reflecting more realistic assumptions. We show that while existing prompted LMAs (gpt45;3.545;turbo or gpt45;4) achieve 94.037; average success rate on base tasks their performance degrades to 24.937; success rate on compositional tasks. On the other hand transferred LMAs (finetuned only on base tasks) show less generalization gap dropping from 85.437; to 54.837;. By balancing data distribution across tasks we train a new model HTML45;T5++ that surpasses human45;level performance (95.237;) on MiniWoB and achieves the best zero45;shot performance on CompWoB (61.537;). While these highlight the promise of small45;scale finetuned and transferred models for task compositionality their performance further degrades under different instruction compositions changing combinational order. In contrast to the recent remarkable success of LMA our benchmark and detailed analysis emphasize the necessity of building LMAs that are robust and generalizable to task compositionality for real45;world deployment.
