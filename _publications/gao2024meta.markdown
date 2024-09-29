---
layout: publication
title: 'Meta Reasoning For Large Language Models'
authors: Gao Peizhong, Xie Ao, Mao Shaoguang, Wu Wenshan, Xia Yan, Mi Haipeng, Wei Furu
conference: "Arxiv"
year: 2024
bibkey: gao2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11698"}
tags: ['Applications', 'Efficiency And Optimization', 'In Context Learning', 'Prompting', 'RAG']
---
We introduce Meta-Reasoning Prompting (MRP) a novel and efficient system prompting method for large language models (LLMs) inspired by human meta-reasoning. Traditional in-context learning-based reasoning techniques such as Tree-of-Thoughts show promise but lack consistent state-of-the-art performance across diverse tasks due to their specialized nature. MRP addresses this limitation by guiding LLMs to dynamically select and apply different reasoning methods based on the specific requirements of each task optimizing both performance and computational efficiency. With MRP LLM reasoning operates in two phases. Initially the LLM identifies the most appropriate reasoning method using task input cues and objective descriptions of available methods. Subsequently it applies the chosen method to complete the task. This dynamic strategy mirrors human meta-reasoning allowing the model to excel in a wide range of problem domains. We evaluate the effectiveness of MRP through comprehensive benchmarks. The results demonstrate that MRP achieves or approaches state-of-the-art performance across diverse tasks. MRP represents a significant advancement in enabling LLMs to identify cognitive challenges across problems and leverage benefits across different reasoning approaches enhancing their ability to handle diverse and complex problem domains efficiently. Every LLM deserves a Meta-Reasoning Prompting to unlock its full potential and ensure adaptability in an ever-evolving landscape of challenges and applications.
