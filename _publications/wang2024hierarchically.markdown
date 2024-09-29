---
layout: publication
title: HPT++&#58; Hierarchically Prompting Vision-language Models With Multi-granularity Knowledge Generation And Improved Structure Modeling
authors: Wang Yubin, Jiang Xinyang, Cheng De, Sun Wenli, Li Dongsheng, Zhao Cairong
conference: "Arxiv"
year: 2024
bibkey: wang2024hierarchically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14812"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Prompt learning has become a prevalent strategy for adapting vision-language foundation models (VLMs) such as CLIP to downstream tasks. With the emergence of large language models (LLMs) recent studies have explored the potential of using category-related descriptions to enhance prompt effectiveness. However conventional descriptions lack explicit structured information necessary to represent the interconnections among key elements like entities or attributes with relation to a particular category. Since existing prompt tuning methods give little consideration to managing structured knowledge this paper advocates leveraging LLMs to construct a graph for each description to prioritize such structured knowledge. Consequently we propose a novel approach called Hierarchical Prompt Tuning (HPT) enabling simultaneous modeling of both structured and conventional linguistic knowledge. Specifically we introduce a relationship-guided attention module to capture pair-wise associations among entities and attributes for low-level prompt learning. In addition by incorporating high-level and global-level prompts modeling overall semantics the proposed hierarchical structure forges cross-level interlinks and empowers the model to handle more complex and long-term relationships. Finally by enhancing multi-granularity knowledge generation redesigning the relationship-driven attention re-weighting module and incorporating consistent constraints on the hierarchical text encoder we propose HPT++ which further improves the performance of HPT. Our experiments are conducted across a wide range of evaluation settings including base-to-new generalization cross-dataset evaluation and domain generalization. Extensive results and ablation studies demonstrate the effectiveness of our methods which consistently outperform existing SOTA methods.
