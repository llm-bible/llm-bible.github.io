---
layout: publication
title: Visual Hallucinations Of Multi45;modal Large Language Models
authors: Huang Wen, Liu Hongbin, Guo Minxin, Gong Neil Zhenqiang
conference: "Arxiv"
year: 2024
bibkey: huang2024visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14683"}
  - {name: "Code", url: "https://github.com/wenhuang2000/VHTest"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture']
---
Visual hallucination (VH) means that a multi45;modal LLM (MLLM) imagines incorrect details about an image in visual question answering. Existing studies find VH instances only in existing image datasets which results in biased understanding of MLLMs performance under VH due to limited diversity of such VH instances. In this work we propose a tool called VHTest to generate a diverse set of VH instances. Specifically VHTest finds some initial VH instances in existing image datasets (e.g. COCO) generates a text description for each VH mode and uses a text45;to45;image generative model (e.g. DALL45;E45;3) to generate VH images based on the text descriptions. We collect a benchmark dataset with 1200 VH instances in 8 VH modes using VHTest. We find that existing MLLMs such as GPT45;4V LLaVA45;1.5 and MiniGPT45;v2 hallucinate for a large fraction of the instances in our benchmark. Moreover we find that fine45;tuning an MLLM using our benchmark dataset reduces its likelihood to hallucinate without sacrificing its performance on other benchmarks. Our benchmarks are publicly available https://github.com/wenhuang2000/VHTest.
