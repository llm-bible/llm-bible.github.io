---
layout: publication
title: Protip Progressive Tool Retrieval Improves Planning
authors: Anantha Raviteja, Bandyopadhyay Bortik, Kashi Anirudh, Mahinder Sayantan, Hill Andrew W, Chappidi Srinivas
conference: "Arxiv"
year: 2023
bibkey: anantha2023progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10332"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) are increasingly employed for complex multi45;step planning tasks where the tool retrieval (TR) step is crucial for achieving successful outcomes. Two prevalent approaches for TR are single45;step retrieval which utilizes the complete query and sequential retrieval using task decomposition (TD) where a full query is segmented into discrete atomic subtasks. While single45;step retrieval lacks the flexibility to handle inter45;tool dependency the TD approach necessitates maintaining subtask45;tool atomicity alignment as the toolbox can evolve dynamically. To address these limitations we introduce the Progressive Tool retrieval to Improve Planning (ProTIP) framework. ProTIP is a lightweight contrastive learning45;based framework that implicitly performs TD without the explicit requirement of subtask labels while simultaneously maintaining subtask45;tool atomicity. On the ToolBench dataset ProTIP outperforms the ChatGPT task decomposition45;based approach by a remarkable margin achieving a 2437; improvement in Recall35;64;K=10 for TR and a 4137; enhancement in tool accuracy for plan generation.
