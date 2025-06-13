---
layout: publication
title: 'Integrating A Heterogeneous Graph With Entity-aware Self-attention Using Relative Position Labels For Reading Comprehension Model'
authors: Shima Foolad, Kourosh Kiani
conference: "Arxiv"
year: 2023
bibkey: foolad2023integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.10443"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Despite the significant progress made by transformer models in machine
reading comprehension tasks, they still fall short in handling complex
reasoning tasks due to the absence of explicit knowledge in the input sequence.
To address this limitation, many recent works have proposed injecting external
knowledge into the model. However, selecting relevant external knowledge,
ensuring its availability, and requiring additional processing steps remain
challenging. In this paper, we introduce a novel attention pattern that
integrates reasoning knowledge derived from a heterogeneous graph into the
transformer architecture without relying on external knowledge. The proposed
attention pattern comprises three key elements: global-local attention for word
tokens, graph attention for entity tokens that exhibit strong attention towards
tokens connected in the graph as opposed to those unconnected, and the
consideration of the type of relationship between each entity token and word
token. This results in optimized attention between the two if a relationship
exists. The pattern is coupled with special relative position labels, allowing
it to integrate with LUKE's entity-aware self-attention mechanism. The
experimental findings corroborate that our model outperforms both the
cutting-edge LUKE-Graph and the baseline LUKE model across two distinct
datasets: ReCoRD, emphasizing commonsense reasoning, and WikiHop, focusing on
multi-hop reasoning challenges.
