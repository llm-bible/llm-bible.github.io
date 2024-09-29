---
layout: publication
title: Learning Hierarchical Prompt with Structured Linguistic Knowledge for Vision-Language Models
authors: Wang Yubin, Jiang Xinyang, Cheng De, Li Dongsheng, Zhao Cairong
conference: "Arxiv"
year: 2023
bibkey: wang2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06323"}
  - {name: "Code", url: "https://github.com/Vill-Lab/2024-AAAI-HPT"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Prompt learning has become a prevalent strategy for adapting vision-language foundation models to downstream tasks. As large language models (LLMs) have emerged recent studies have explored the use of category-related descriptions as input to enhance prompt effectiveness. Nevertheless conventional descriptions fall short of structured information that effectively represents the interconnections among entities or attributes linked to a particular category. To address this limitation and prioritize harnessing structured knowledge this paper advocates for leveraging LLMs to build a graph for each description to model the entities and attributes describing the category as well as their correlations. Preexisting prompt tuning methods exhibit inadequacies in managing this structured knowledge. Consequently we propose a novel approach called Hierarchical Prompt Tuning (HPT) which enables simultaneous modeling of both structured and conventional linguistic knowledge. Specifically we introduce a relationship-guided attention module to capture pair-wise associations among entities and attributes for low-level prompt learning. In addition by incorporating high-level and global-level prompts modeling overall semantics the proposed hierarchical structure forges cross-level interlinks and empowers the model to handle more complex and long-term relationships. Extensive experiments demonstrate that our HPT shows strong effectiveness and generalizes much better than existing SOTA methods. Our code is available at https://github.com/Vill-Lab/2024-AAAI-HPT.
