---
layout: publication
title: Choice Fusion As Knowledge For Zero45;shot Dialogue State Tracking
authors: Su Ruolin, Yang Jingfeng, Wu Ting-wei, Juang Biing-hwang
conference: "Arxiv"
year: 2023
bibkey: su2023choice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.13013"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'RAG', 'Training Techniques']
---
With the demanding need for deploying dialogue systems in new domains with less cost zero45;shot dialogue state tracking (DST) which tracks users requirements in task45;oriented dialogues without training on desired domains draws attention increasingly. Although prior works have leveraged question45;answering (QA) data to reduce the need for in45;domain training in DST they fail to explicitly model knowledge transfer and fusion for tracking dialogue states. To address this issue we propose CoFunDST which is trained on domain45;agnostic QA datasets and directly uses candidate choices of slot45;values as knowledge for zero45;shot dialogue45;state generation based on a T5 pre45;trained language model. Specifically CoFunDST selects highly45;relevant choices to the reference context and fuses them to initialize the decoder to constrain the model outputs. Our experimental results show that our proposed model achieves outperformed joint goal accuracy compared to existing zero45;shot DST approaches in most domains on the MultiWOZ 2.1. Extensive analyses demonstrate the effectiveness of our proposed approach for improving zero45;shot DST learning from QA.
