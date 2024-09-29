---
layout: publication
title: Context-faithful Prompting for Large Language Models
authors: Zhou Wenxuan, Zhang Sheng, Poon Hoifung, Chen Muhao
conference: "Arxiv"
year: 2023
bibkey: zhou2023context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.11315"}
  - {name: "Code", url: "https://github.com/wzhouad/context-faithful-llm"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) encode parametric knowledge about world facts and have shown remarkable performance in knowledge-driven NLP tasks. However their reliance on parametric knowledge may cause them to overlook contextual cues leading to incorrect predictions in context-sensitive NLP tasks (e.g. knowledge acquisition tasks). In this paper we seek to assess and enhance LLMs contextual faithfulness in two aspects knowledge conflict and prediction with abstention. We demonstrate that LLMs faithfulness can be significantly improved using carefully designed prompting strategies. In particular we identify opinion-based prompts and counterfactual demonstrations as the most effective methods. Opinion-based prompts reframe the context as a narrators statement and inquire about the narrators opinions while counterfactual demonstrations use instances containing false facts to improve faithfulness in knowledge conflict situations. Neither technique requires additional training. We conduct experiments on three datasets of two standard NLP tasks machine reading comprehension and relation extraction and the results demonstrate significant improvement in faithfulness to contexts. Code and data are released at https://github.com/wzhouad/context-faithful-llm.
