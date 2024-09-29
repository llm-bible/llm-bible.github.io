---
layout: publication
title: 'Does Entity Abstraction Help Generative Transformers Reason?'
authors: Gontier Nicolas, Reddy Siva, Pal Christopher
conference: "Arxiv"
year: 2022
bibkey: gontier2022does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.01787"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
We study the utility of incorporating entity type abstractions into pre-trained Transformers and test these methods on four NLP tasks requiring different forms of logical reasoning (1) compositional language understanding with text-based relational reasoning (CLUTRR) (2) abductive reasoning (ProofWriter) (3) multi-hop question answering (HotpotQA) and (4) conversational question answering (CoQA). We propose and empirically explore three ways to add such abstraction (i) as additional input embeddings (ii) as a separate sequence to encode and (iii) as an auxiliary prediction task for the model. Overall our analysis demonstrates that models with abstract entity knowledge performs better than without it. The best abstraction aware models achieved an overall accuracy of 88.837; and 91.837; compared to the baseline model achieving 62.937; and 89.837; on CLUTRR and ProofWriter respectively. However for HotpotQA and CoQA we find that F1 scores improve by only 0.537; on average. Our results suggest that the benefit of explicit abstraction is significant in formally defined logical reasoning settings requiring many reasoning hops but point to the notion that it is less beneficial for NLP tasks having less formal logical structure.
