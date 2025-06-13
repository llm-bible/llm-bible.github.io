---
layout: publication
title: 'Dockd: Knowledge Distillation From Llms For Open-world Document Understanding Models'
authors: Sungnyun Kim, Haofu Liao, Srikar Appalaraju, Peng Tang, Zhuowen Tu, Ravi Kumar Satzoda, R. Manmatha, Vijay Mahadevan, Stefano Soatto
conference: "Arxiv"
year: 2024
bibkey: kim2024knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03061'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Visual document understanding (VDU) is a challenging task that involves
understanding documents across various modalities (text and image) and layouts
(forms, tables, etc.). This study aims to enhance generalizability of small VDU
models by distilling knowledge from LLMs. We identify that directly prompting
LLMs often fails to generate informative and useful data. In response, we
present a new framework (called DocKD) that enriches the data generation
process by integrating external document knowledge. Specifically, we provide an
LLM with various document elements like key-value pairs, layouts, and
descriptions, to elicit open-ended answers. Our experiments show that DocKD
produces high-quality document annotations and surpasses the direct knowledge
distillation approach that does not leverage external document knowledge.
Moreover, student VDU models trained with solely DocKD-generated data are not
only comparable to those trained with human-annotated data on in-domain tasks
but also significantly excel them on out-of-domain tasks.
