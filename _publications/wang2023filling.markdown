---
layout: publication
title: "Filling The Image Information Gap For VQA: Prompting Large Language Models To Proactively Ask Questions"
authors: Wang Ziyue, Chen Chi, Li Peng, Liu Yang
conference: "https://aclanthology.org/"
year: 2023
bibkey: wang2023filling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11598"}
tags: ['Applications', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) demonstrate impressive reasoning ability and the maintenance of world knowledge not only in natural language tasks but also in some vision-language tasks such as open-domain knowledge-based visual question answering (OK-VQA). As images are invisible to LLMs researchers convert images to text to engage LLMs into the visual question reasoning procedure. This leads to discrepancies between images and their textual representations presented to LLMs which consequently impedes final reasoning performance. To fill the information gap and better leverage the reasoning capability we design a framework that enables LLMs to proactively ask relevant questions to unveil more details in the image along with filters for refining the generated information. We validate our idea on OK-VQA and A-OKVQA. Our method continuously boosts the performance of baselines methods by an average gain of 2.1537; on OK-VQA and achieves consistent improvements across different LLMs.
