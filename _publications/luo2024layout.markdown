---
layout: publication
title: Layoutllm Layout Instruction Tuning With Large Language Models For Document Understanding
authors: Luo Chuwei, Shen Yufan, Zhu Zhaoqing, Zheng Qi, Yu Zhi, Yao Cong
conference: "Arxiv"
year: 2024
bibkey: luo2024layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05225"}
  - {name: "Code", url: "https://github.com/AlibabaResearch/AdvancedLiterateMachinery/tree/main/DocumentUnderstanding/LayoutLLM"}
tags: ['Has Code', 'Interpretability And Explainability', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Recently leveraging large language models (LLMs) or multimodal large language models (MLLMs) for document understanding has been proven very promising. However previous works that employ LLMs/MLLMs for document understanding have not fully explored and utilized the document layout information which is vital for precise document understanding. In this paper we propose LayoutLLM an LLM/MLLM based method for document understanding. The core of LayoutLLM is a layout instruction tuning strategy which is specially designed to enhance the comprehension and utilization of document layouts. The proposed layout instruction tuning strategy consists of two components Layout45;aware Pre45;training and Layout45;aware Supervised Fine45;tuning. To capture the characteristics of document layout in Layout45;aware Pre45;training three groups of pre45;training tasks corresponding to document45;level region45;level and segment45;level information are introduced. Furthermore a novel module called layout chain45;of45;thought (LayoutCoT) is devised to enable LayoutLLM to focus on regions relevant to the question and generate accurate answers. LayoutCoT is effective for boosting the performance of document understanding. Meanwhile it brings a certain degree of interpretability which could facilitate manual inspection and correction. Experiments on standard benchmarks show that the proposed LayoutLLM significantly outperforms existing methods that adopt open45;source 7B LLMs/MLLMs for document understanding. The training data of the LayoutLLM is publicly available at https://github.com/AlibabaResearch/AdvancedLiterateMachinery/tree/main/DocumentUnderstanding/LayoutLLM
