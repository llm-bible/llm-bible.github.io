---
layout: publication
title: HPT++ Hierarchically Prompting Vision45;language Models With Multi45;granularity Knowledge Generation And Improved Structure Modeling
authors: Wang Yubin, Jiang Xinyang, Cheng De, Sun Wenli, Li Dongsheng, Zhao Cairong
conference: "Arxiv"
year: 2024
bibkey: wang2024hierarchically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14812"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Prompt learning has become a prevalent strategy for adapting vision45;language foundation models (VLMs) such as CLIP to downstream tasks. With the emergence of large language models (LLMs) recent studies have explored the potential of using category45;related descriptions to enhance prompt effectiveness. However conventional descriptions lack explicit structured information necessary to represent the interconnections among key elements like entities or attributes with relation to a particular category. Since existing prompt tuning methods give little consideration to managing structured knowledge this paper advocates leveraging LLMs to construct a graph for each description to prioritize such structured knowledge. Consequently we propose a novel approach called Hierarchical Prompt Tuning (HPT) enabling simultaneous modeling of both structured and conventional linguistic knowledge. Specifically we introduce a relationship45;guided attention module to capture pair45;wise associations among entities and attributes for low45;level prompt learning. In addition by incorporating high45;level and global45;level prompts modeling overall semantics the proposed hierarchical structure forges cross45;level interlinks and empowers the model to handle more complex and long45;term relationships. Finally by enhancing multi45;granularity knowledge generation redesigning the relationship45;driven attention re45;weighting module and incorporating consistent constraints on the hierarchical text encoder we propose HPT++ which further improves the performance of HPT. Our experiments are conducted across a wide range of evaluation settings including base45;to45;new generalization cross45;dataset evaluation and domain generalization. Extensive results and ablation studies demonstrate the effectiveness of our methods which consistently outperform existing SOTA methods.
