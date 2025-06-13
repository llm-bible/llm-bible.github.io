---
layout: publication
title: 'How Does Knowledge Selection Help Retrieval Augmented Generation?'
authors: Xiangci Li, Jessica Ouyang
conference: "Arxiv"
year: 2024
bibkey: li2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13258"}
tags: ['RAG']
---
Retrieval-augmented generation (RAG) is a powerful method for enhancing natural language generation by integrating external knowledge into a model's output. While prior work has demonstrated the importance of improving knowledge retrieval for boosting generation quality, the role of knowledge selection remains less clear. This paper empirically analyzes how knowledge selection influences downstream generation performance in RAG systems. By simulating different retrieval and selection conditions through a controlled mixture of gold and distractor knowledge, we assess the impact of these factors on generation outcomes. Our findings indicate that the downstream generator model's capability, as well as the complexity of the task and dataset, significantly influence the impact of knowledge selection on the overall RAG system performance. In typical scenarios, improving the knowledge recall score is key to enhancing generation outcomes, with the knowledge selector providing limited benefit when a strong generator model is used on clear, well-defined tasks. For weaker generator models or more ambiguous tasks and datasets, the knowledge F1 score becomes a critical factor, and the knowledge selector plays a more prominent role in improving overall performance.
