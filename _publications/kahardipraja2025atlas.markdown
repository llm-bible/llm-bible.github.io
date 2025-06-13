---
layout: publication
title: 'The Atlas Of In-context Learning: How Attention Heads Shape In-context Retrieval Augmentation'
authors: Patrick Kahardipraja, Reduan Achtibat, Thomas Wiegand, Wojciech Samek, Sebastian Lapuschkin
conference: "Arxiv"
year: 2025
bibkey: kahardipraja2025atlas
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15807"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'In-Context Learning', 'Prompting', 'Applications', 'Attention Mechanism']
---
Large language models are able to exploit in-context learning to access external knowledge beyond their training data through retrieval-augmentation. While promising, its inner workings remain unclear. In this work, we shed light on the mechanism of in-context retrieval augmentation for question answering by viewing a prompt as a composition of informational components. We propose an attribution-based method to identify specialized attention heads, revealing in-context heads that comprehend instructions and retrieve relevant contextual information, and parametric heads that store entities' relational knowledge. To better understand their roles, we extract function vectors and modify their attention weights to show how they can influence the answer generation process. Finally, we leverage the gained insights to trace the sources of knowledge used during inference, paving the way towards more safe and transparent language models.
