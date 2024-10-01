---
layout: publication
title: 'Learning To Memorize In Neural Task-oriented Dialogue Systems'
authors: Wu Chien-sheng
conference: "Arxiv"
year: 2019
bibkey: wu2019learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.07687"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Model Architecture', 'RAG']
---
In this thesis, we leverage the neural copy mechanism and memory-augmented neural networks (MANNs) to address existing challenge of neural task-oriented dialogue learning. We show the effectiveness of our strategy by achieving good performance in multi-domain dialogue state tracking, retrieval-based dialogue systems, and generation-based dialogue systems. We first propose a transferable dialogue state generator (TRADE) that leverages its copy mechanism to get rid of dialogue ontology and share knowledge between domains. We also evaluate unseen domain dialogue state tracking and show that TRADE enables zero-shot dialogue state tracking and can adapt to new few-shot domains without forgetting the previous domains. Second, we utilize MANNs to improve retrieval-based dialogue learning. They are able to capture dialogue sequential dependencies and memorize long-term information. We also propose a recorded delexicalization copy strategy to replace real entity values with ordered entity types. Our models are shown to surpass other retrieval baselines, especially when the conversation has a large number of turns. Lastly, we tackle generation-based dialogue learning with two proposed models, the memory-to-sequence (Mem2Seq) and global-to-local memory pointer network (GLMP). Mem2Seq is the first model to combine multi-hop memory attention with the idea of the copy mechanism. GLMP further introduces the concept of response sketching and double pointers copying. We show that GLMP achieves the state-of-the-art performance on human evaluation.
