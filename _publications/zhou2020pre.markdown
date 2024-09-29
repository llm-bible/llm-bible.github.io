---
layout: publication
title: Pre45;training Text45;to45;text Transformers For Concept45;centric Common Sense
authors: Zhou Wangchunshu, Lee Dong-ho, Selvam Ravi Kiran, Lee Seyeon, Lin Bill Yuchen, Ren Xiang
conference: "Arxiv"
year: 2020
bibkey: zhou2020pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.07956"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Pre45;trained language models (PTLM) have achieved impressive results in a range of natural language understanding (NLU) and generation (NLG) tasks. However current pre45;training objectives such as masked token prediction (for BERT45;style PTLMs) and masked span infilling (for T545;style PTLMs) do not explicitly model the relational commonsense knowledge about everyday concepts which is crucial to many downstream tasks that need common sense to understand or generate. To augment PTLMs with concept45;centric commonsense knowledge in this paper we propose both generative and contrastive objectives for learning common sense from the text and use them as intermediate self45;supervised learning tasks for incrementally pre45;training PTLMs (before task45;specific fine45;tuning on downstream datasets). Furthermore we develop a joint pre45;training framework to unify generative and contrastive objectives so that they can mutually reinforce each other. Extensive experimental results show that our method concept45;aware language model (CALM) can pack more commonsense knowledge into the parameters of a pre45;trained text45;to45;text transformer without relying on external knowledge graphs yielding better performance on both NLU and NLG tasks. We show that while only incrementally pre45;trained on a relatively small corpus for a few steps CALM outperforms baseline methods by a consistent margin and even comparable with some larger PTLMs which suggests that CALM can serve as a general plug45;and45;play method for improving the commonsense reasoning ability of a PTLM.
