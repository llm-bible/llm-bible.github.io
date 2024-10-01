---
layout: publication
title: 'Protip: Progressive Tool Retrieval Improves Planning'
authors: Anantha Raviteja, Bandyopadhyay Bortik, Kashi Anirudh, Mahinder Sayantan, Hill Andrew W, Chappidi Srinivas
conference: "Arxiv"
year: 2023
bibkey: anantha2023progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10332"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) are increasingly employed for complex multi-step planning tasks, where the tool retrieval (TR) step is crucial for achieving successful outcomes. Two prevalent approaches for TR are single-step retrieval, which utilizes the complete query, and sequential retrieval using task decomposition (TD), where a full query is segmented into discrete atomic subtasks. While single-step retrieval lacks the flexibility to handle inter-tool dependency, the TD approach necessitates maintaining subtask-tool atomicity alignment, as the toolbox can evolve dynamically. To address these limitations, we introduce the Progressive Tool retrieval to Improve Planning (ProTIP) framework. ProTIP is a lightweight, contrastive learning-based framework that implicitly performs TD without the explicit requirement of subtask labels, while simultaneously maintaining subtask-tool atomicity. On the ToolBench dataset, ProTIP outperforms the ChatGPT task decomposition-based approach by a remarkable margin, achieving a 24&#37; improvement in Recall@K=10 for TR and a 41&#37; enhancement in tool accuracy for plan generation.
