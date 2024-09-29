---
layout: publication
title: MATTER Memory45;augmented Transformer Using Heterogeneous Knowledge Sources
authors: Lee Dongkyu, Prakash Chandana Satya, Fitzgerald Jack, Lehmann Jens
conference: "Arxiv"
year: 2024
bibkey: lee2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04670"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Leveraging external knowledge is crucial for achieving high performance in knowledge45;intensive tasks such as question answering. The retrieve45;and45;read approach is widely adopted for integrating external knowledge into a language model. However this approach suffers from increased computational cost and latency due to the long context length which grows proportionally with the number of retrieved knowledge. Furthermore existing retrieval45;augmented models typically retrieve information from a single type of knowledge source limiting their scalability to diverse knowledge sources with varying structures. In this work we introduce an efficient memory45;augmented transformer called MATTER designed to retrieve relevant knowledge from multiple heterogeneous knowledge sources. Specifically our model retrieves and reads from both unstructured sources (paragraphs) and semi45;structured sources (QA pairs) in the form of fixed45;length neural memories. We demonstrate that our model outperforms existing efficient retrieval45;augmented models on popular QA benchmarks in terms of both accuracy and speed. Furthermore MATTER achieves competitive results compared to conventional read45;and45;retrieve models while having 100x throughput during inference.
