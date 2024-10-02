---
layout: publication
title: 'Translate-and-revise: Boosting Large Language Models For Constrained Translation'
authors: Huang Pengcheng, Mu Yongyu, Wu Yuzhang, Li Bei, Xiao Chunyang, Xiao Tong, Zhu Jingbo
conference: "Arxiv"
year: 2024
bibkey: huang2024translate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13164"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning']
---
'Imposing constraints on machine translation systems presents a challenging issue because these systems are not trained to make use of constraints in generating adequate, fluent translations. In this paper, we leverage the capabilities of large language models (LLMs) for constrained translation, given that LLMs can easily adapt to this task by taking translation instructions and constraints as prompts. However, LLMs cannot always guarantee the adequacy of translation, and, in some cases, ignore the given constraints. This is in part because LLMs might be overly confident in their predictions, overriding the influence of the constraints. To overcome this overiding behaviour, we propose to add a revision process that encourages LLMs to correct the outputs by prompting them about the constraints that have not yet been met. We evaluate our approach on four constrained translation tasks, encompassing both lexical and structural constraints in multiple constraint domains. Experiments show 15\&#37; improvement in constraint-based translation accuracy over standard LLMs and the approach also significantly outperforms neural machine translation (NMT) state-of-the-art methods.'
