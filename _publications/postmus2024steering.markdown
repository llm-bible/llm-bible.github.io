---
layout: publication
title: 'Steering Large Language Models Using Conceptors: Improving Addition-based Activation Engineering'
authors: Joris Postmus, Steven Abreu
conference: "Arxiv"
year: 2024
bibkey: postmus2024steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16314"}
tags: ['Uncategorized']
---
Large language models have transformed AI, yet reliably controlling their outputs remains a challenge. This paper explores activation engineering, where outputs of pre-trained LLMs are controlled by manipulating their activations at inference time. Unlike traditional methods using a single steering vector, we introduce conceptors - mathematical constructs that represent sets of activation vectors as ellipsoidal regions. Conceptors act as soft projection matrices and offer more precise control over complex activation patterns. Our experiments demonstrate that conceptors outperform traditional methods across multiple steering tasks. We further use Boolean operations on conceptors for combined steering goals that empirically outperform additively combining steering vectors on a set of tasks. These results highlight conceptors as a promising tool for more effective steering of LLMs. Our code is available on github.com/jorispos/conceptorsteering.
