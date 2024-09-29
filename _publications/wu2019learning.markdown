---
layout: publication
title: Learning To Memorize In Neural Task45;oriented Dialogue Systems
authors: Wu Chien-sheng
conference: "Arxiv"
year: 2019
bibkey: wu2019learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.07687"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG']
---
In this thesis we leverage the neural copy mechanism and memory45;augmented neural networks (MANNs) to address existing challenge of neural task45;oriented dialogue learning. We show the effectiveness of our strategy by achieving good performance in multi45;domain dialogue state tracking retrieval45;based dialogue systems and generation45;based dialogue systems. We first propose a transferable dialogue state generator (TRADE) that leverages its copy mechanism to get rid of dialogue ontology and share knowledge between domains. We also evaluate unseen domain dialogue state tracking and show that TRADE enables zero45;shot dialogue state tracking and can adapt to new few45;shot domains without forgetting the previous domains. Second we utilize MANNs to improve retrieval45;based dialogue learning. They are able to capture dialogue sequential dependencies and memorize long45;term information. We also propose a recorded delexicalization copy strategy to replace real entity values with ordered entity types. Our models are shown to surpass other retrieval baselines especially when the conversation has a large number of turns. Lastly we tackle generation45;based dialogue learning with two proposed models the memory45;to45;sequence (Mem2Seq) and global45;to45;local memory pointer network (GLMP). Mem2Seq is the first model to combine multi45;hop memory attention with the idea of the copy mechanism. GLMP further introduces the concept of response sketching and double pointers copying. We show that GLMP achieves the state45;of45;the45;art performance on human evaluation.
